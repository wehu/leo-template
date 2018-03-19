package(default_visibility = ["//visibility:public"])
load("@lionrock//rules:cmn.bzl", "block", "verilator_library")

block(
    name = "dut_v",
    srcs = glob([
        "*.v",
    ]),
    deps = ["//:leo_features"],
    includes = ["."],
)

verilator_library(
    name = "dut",
    deps = [":dut_v"],
)

