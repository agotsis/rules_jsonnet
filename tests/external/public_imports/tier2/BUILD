load(
    "@io_bazel_rules_jsonnet//jsonnet:jsonnet.bzl",
    "jsonnet_library",
)

jsonnet_library(
    name = "c",
    srcs = ["c.libsonnet"],
    imports = ["../"],
    deps = ["//public_imports:d"],
    visibility = ["//public_imports/tier2/tier3:__pkg__"],
)
