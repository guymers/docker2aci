load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "pop_linux.go",
        "pop_posix.go",
        "tarheader.go",
    ],
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/appc/spec/pkg/device:go_default_library"],
)
