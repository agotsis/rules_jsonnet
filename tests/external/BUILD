package(default_visibility = ["//visibility:public"])

# This directory contains unit and regression tests that also serve as examples
# for jsonnet rules.

load(
    "@io_bazel_rules_jsonnet//jsonnet:jsonnet.bzl",
    "jsonnet_to_json_test",
    "jsonnet_to_json",
)

jsonnet_to_json(
    name = "simple_substitution",
    src = "simple_substitution.jsonnet",
    outs = ["simple_substitution.json"]
)

jsonnet_to_json_test(
    name = "simple_substitution_test",
    src = "simple_substitution.jsonnet",
    golden = "simple_substitution_golden.json",
)