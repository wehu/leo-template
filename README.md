# leo-template

This is a template based on lionrock[https://github.com/wehu/lionrock]

By default, use verilator as simulator, plus systemc, scv and uvm-systemc for co-simulation testbench.


## require

* bazel: https://docs.bazel.build/versions/master/install.html
* make

## tree

* rtl: verilog rtl code
* tb: testbench based on uvm-systemc
* tests: test definitons

## run smoke tests

`bazel test tests:smoke_tests`
