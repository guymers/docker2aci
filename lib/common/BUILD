load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["common.go"],
    visibility = ["//visibility:public"],
    deps = [
        "//lib/internal/docker:go_default_library",
        "//vendor/github.com/docker/distribution/reference:go_default_library",
        "//vendor/github.com/opencontainers/image-spec/specs-go/v1:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["common_test.go"],
    library = ":go_default_library",
)
