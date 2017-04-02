load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["util.go"],
    visibility = ["//lib:__subpackages__"],
    deps = ["//vendor/github.com/appc/spec/pkg/acirenderer:go_default_library"],
)
