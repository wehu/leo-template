workspace(name = "leo_template")

git_repository(
    name = "lionrock",
    remote = "http://github.com/wehu/lionrock.git",
    commit = "54f5434097edd04c022c07a16bd52ee0da4e530b",
)

local_repository(
    name = "foo",
    path = "../foo",
)

new_http_archive(
    name = "verilator",
    urls = ["https://github.com/wehu/lionrock/releases/download/v0.1/verilator-2018-03-18.tar.gz"],
    sha256 = "4a8f7151cbac8d705c8594680cec975e4b4d0fec59f0b98db8552158bbd57491",
    build_file = "@lionrock//:verilator.BUILD",
)

new_http_archive(
    name = "systemc",
    urls = ["https://github.com/wehu/lionrock/releases/download/v0.1/systemc-2.3.2.tar.gz"],
    sha256 = "16c0926d102ee56ad9687a81e45f6dfdd2cf34ec13d416f43faa545c49a9aaca",
    build_file = "@lionrock//:systemc.BUILD",
)

new_http_archive(
    name = "uvm_systemc",
    urls = ["https://github.com/wehu/lionrock/releases/download/v0.1/uvm-systemc-1.0-beta1.tar.gz"],
    sha256 = "6e31c8312b2a0abd82db746b615ea77956431e74270425d7d609368194253118",
    build_file = "@lionrock//:uvm-systemc.BUILD",
)

