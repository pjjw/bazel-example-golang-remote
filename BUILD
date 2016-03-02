load("@bazel_tools//tools/build_rules/go:def.bzl", "go_prefix", "go_library")

go_prefix("github.com/lar/bazel-example-golang-remote")

go_library(
    name = "remote",
    srcs = [ "remote.go" ],
    visibility = ["//visibility:public"],
)
