load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["internal.go"],
    visibility = ["//visibility:public"],
    deps = [
        "//lib/common:go_default_library",
        "//lib/internal/tarball:go_default_library",
        "//lib/internal/types:go_default_library",
        "//lib/internal/typesV2:go_default_library",
        "//lib/internal/util:go_default_library",
        "//pkg/log:go_default_library",
        "//vendor/github.com/appc/spec/aci:go_default_library",
        "//vendor/github.com/appc/spec/schema:go_default_library",
        "//vendor/github.com/appc/spec/schema/types:go_default_library",
        "//vendor/github.com/klauspost/pgzip:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["internal_test.go"],
    library = ":go_default_library",
    deps = ["//vendor/github.com/appc/spec/schema/types:go_default_library"],
)
