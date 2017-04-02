load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library", "go_prefix")

go_prefix("github.com/appc/docker2aci")

go_library(
    name = "go_default_library",
    srcs = ["main.go"],
    visibility = ["//visibility:private"],
    deps = [
        "//lib:go_default_library",
        "//lib/common:go_default_library",
        "//pkg/log:go_default_library",
        "//vendor/github.com/appc/spec/aci:go_default_library",
        "//vendor/github.com/appc/spec/schema:go_default_library",
    ],
)

go_binary(
    name = "docker2aci",
    library = ":go_default_library",
    visibility = ["//visibility:public"],
)
