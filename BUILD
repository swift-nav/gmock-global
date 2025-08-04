load("@rules_cc//cc:defs.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "gmock-global",
    srcs = glob(
        ["*/**/*.cpp"],
        allow_empty = True,
    ),
    hdrs = glob(["*/**/*.h"]),
    includes = [
        "include",
    ],
    strip_include_prefix = "include",
)
