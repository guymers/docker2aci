load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conversion_store.go",
        "docker2aci.go",
        "version.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//lib/common:go_default_library",
        "//lib/internal:go_default_library",
        "//lib/internal/backend/file:go_default_library",
        "//lib/internal/backend/repository:go_default_library",
        "//lib/internal/docker:go_default_library",
        "//lib/internal/tarball:go_default_library",
        "//lib/internal/util:go_default_library",
        "//pkg/log:go_default_library",
        "//vendor/github.com/appc/spec/aci:go_default_library",
        "//vendor/github.com/appc/spec/pkg/acirenderer:go_default_library",
        "//vendor/github.com/appc/spec/schema:go_default_library",
        "//vendor/github.com/appc/spec/schema/types:go_default_library",
        "//vendor/github.com/klauspost/pgzip:go_default_library",
    ],
)
