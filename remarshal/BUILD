load("@pip//:requirements.bzl", "requirement")
load("@subpar//:subpar.bzl", "par_binary")

par_binary(
    name = "remarshal",
    srcs = ["remarshal.py"],
    visibility = ["//visibility:public"],
    deps = [
        requirement("PyYAML"),
        requirement("python-dateutil"),
        requirement("pytoml"),
        requirement("remarshal"),
        requirement("six"),
    ],
)
