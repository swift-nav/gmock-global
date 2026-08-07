load("@rules_cc//cc:cc_library.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "gmock-global",
    hdrs = glob(["*/**/*.h"]),
    includes = [
        "include",
    ],
    strip_include_prefix = "include",
)
