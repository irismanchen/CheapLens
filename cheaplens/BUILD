package(
        default_visibility = ["//visibility:public"],
)

cc_library(
        name = "calibration",
        srcs = ["calibration.cc"],
        hdrs = ["calibration.hpp"],
)

cc_library(
        name = "pose",
        srcs = ["pose.cc"],
        hdrs = ["pose.hpp"],
)

cc_library(
        name = "render",
        srcs = ["render.cc"],
        hdrs = ["render.hpp"],
)

cc_library(
        name = "cheaplens",
        srcs = ["cheaplens.cc"],
        hdrs = ["cheaplens.hpp"],
        deps = [
                ":calibration",
                ":pose",
                ":render",
                "@opencv//:opencv",
        ],
)
