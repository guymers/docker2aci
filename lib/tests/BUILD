load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "common.go",
        "server.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//lib/common:go_default_library",
        "//lib/internal/typesV2:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["v22_test.go"],
    library = ":go_default_library",
    deps = [
        "//lib:go_default_library",
        "//lib/common:go_default_library",
        "//lib/internal/typesV2:go_default_library",
        "//vendor/github.com/appc/spec/aci:go_default_library",
        "//vendor/github.com/appc/spec/schema:go_default_library",
        "//vendor/github.com/appc/spec/schema/types:go_default_library",
    ],
)
