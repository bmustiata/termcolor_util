load("//build/bazel:python.bzl", "python_library", "python_binary", "python_docker_container")


python_library(
  name="termcolor-util",
  version="1.0",
  srcs=glob(["termcolor_util/__init__.py"]),
  deps=["//thirdparty/python:termcolor"],
)

python_binary(
  name="termcolor-util-binary",
  deps=[
    ":termcolor-util"
  ],
  main="termcolor_util/__main__.py",
)

python_docker_container(
  name="termcolor-util-binary-docker-container",
  binary=":termcolor-util-binary",
)
