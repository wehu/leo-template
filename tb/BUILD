load("@lionrock//rules:cmn.bzl", "block")

cc_binary(
    name = "bfm",
    srcs = glob(["*.cpp",
            "*.h"]) +
           ["//rtl:dut.a",
            "//rtl:dut.h",
            "//rtl:verilated.o",
           ],
    deps = ["@verilator//:verilator", "@uvm_systemc//:uvm_systemc"],
    visibility = ["//visibility:public"],
)


