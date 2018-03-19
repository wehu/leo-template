load("@lionrock//rules:cmn.bzl", "new_test")

new_test(
  name = "dashboard_demo",
  config = "//tb:bfm",
  size = "small",
)

test_suite(
    name = "smoke_tests",
    tests = [
        "dashboard_demo",
    ],
)

