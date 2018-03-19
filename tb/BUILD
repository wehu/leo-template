load("@lionrock//rules:cmn.bzl", "block")

cc_binary(
    name = "bfm",
    srcs = glob(["*.cpp",
            "*.h"]) +
           ["//src/rtl:dut.a",
            "//src/rtl:dut.h",
            "//src/rtl:verilated.o",
           ],
    deps = ["@verilator//:verilator", "@uvm_systemc//:uvm_systemc"],
    visibility = ["//visibility:public"],
)


