# Description:
# Contains script to generate tensorflow/core/util/version_info.cc
# Also contains information about git repository deposited by configure
# in gen/...
package(default_visibility = ["//tensorflow:internal"])

licenses(["notice"])  # Apache 2.0

py_binary(
    name = "gen_git_source",
    srcs = ["gen_git_source.py"],
    python_version = "PY2",
    srcs_version = "PY2AND3",
)
