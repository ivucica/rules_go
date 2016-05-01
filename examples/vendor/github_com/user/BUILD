package(
    default_visibility = ["//visibility:public"],
)

load("//go:def.bzl", "go_library")

go_library(
    name = "vendored",
    srcs = [
        "vendored_without_buildfile/vendored.go",
    ],
    source_import = "github_com/user/vendored",
)
