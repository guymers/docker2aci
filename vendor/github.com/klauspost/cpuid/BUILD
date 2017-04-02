load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cpuid.go",
        "cpuid_amd64.s",
        "detect_intel.go",
        "generate.go",
    ],
    visibility = ["//visibility:public"],
)
