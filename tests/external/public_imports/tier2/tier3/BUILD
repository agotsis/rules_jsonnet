load(
    "@io_bazel_rules_jsonnet//jsonnet:jsonnet.bzl",
    "jsonnet_library",
)

jsonnet_library(
    name = "b",
    srcs = ["b.libsonnet"],
    imports = ["../"],
    deps = ["//public_imports/tier2:c"],
    visibility = ["//public_imports:__pkg__"],
)
