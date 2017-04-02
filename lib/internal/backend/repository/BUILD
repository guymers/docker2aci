load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "repository.go",
        "repository1.go",
        "repository2.go",
    ],
    visibility = ["//lib:__subpackages__"],
    deps = [
        "//lib/common:go_default_library",
        "//lib/internal:go_default_library",
        "//lib/internal/types:go_default_library",
        "//lib/internal/typesV2:go_default_library",
        "//lib/internal/util:go_default_library",
        "//pkg/log:go_default_library",
        "//vendor/github.com/appc/spec/schema:go_default_library",
        "//vendor/github.com/coreos/ioprogress:go_default_library",
        "//vendor/github.com/coreos/pkg/progressutil:go_default_library",
        "//vendor/github.com/opencontainers/go-digest:go_default_library",
    ],
)
