load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "draw.go",
        "reader.go",
    ],
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/crypto/ssh/terminal:go_default_library"],
)
