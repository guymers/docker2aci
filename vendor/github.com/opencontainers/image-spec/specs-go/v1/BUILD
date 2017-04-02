load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "config.go",
        "descriptor.go",
        "manifest.go",
        "manifest_list.go",
        "mediatype.go",
    ],
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/opencontainers/image-spec/specs-go:go_default_library"],
)
