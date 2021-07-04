load("//build/bazel:python.bzl", "python_library", "python_binary")


python_library(
    name="termcolor-util",
    srcs=glob(["termcolor_util/__init__.py"]),
    deps=["//thirdparty/python:termcolor"],
)

python_binary(
    name="termcolor-util-binary",
    deps=[":termcolor_util"],
    main="termcolor_util/__main__.py",
)

