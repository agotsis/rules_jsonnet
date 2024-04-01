load(
    "@io_bazel_rules_jsonnet//jsonnet:jsonnet.bzl",
    "jsonnet_library",
)

jsonnet_library(
    name = "a",
    srcs = ["a.libsonnet"],
    imports = ["tier2/tier3"],
    visibility = ["//visibility:public"],
    deps = ["//public_imports/tier2/tier3:b"],
)

jsonnet_library(
    name = "d",
    srcs = ["d.libsonnet"],
    visibility = ["//public_imports/tier2:__pkg__"],
)
