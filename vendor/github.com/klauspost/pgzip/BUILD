load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "gunzip.go",
        "gzip.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/klauspost/compress/flate:go_default_library",
        "//vendor/github.com/klauspost/crc32:go_default_library",
    ],
)
