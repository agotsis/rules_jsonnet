package(default_visibility = ["//visibility:public"])

# This directory contains unit and regression tests that also serve as examples
# for jsonnet rules.

load(
    "@io_bazel_rules_jsonnet//jsonnet:jsonnet.bzl",
    "jsonnet_library",
    "jsonnet_to_json_test",
    "jsonnet_to_json",
)

jsonnet_to_json(
    name = "imports_test_external_deps",
    src = "imports.jsonnet",
    # golden = "imports_external_golden.json",
    deps = ["@external//public_imports:a"],
    outs = ["ext_imports.json"]
)