load("@termcolor-util-pip//:requirements.bzl", "requirement")
load("@io_bazel_rules_docker//python3:image.bzl", py3_image="py3_image")

py_library(
  name='termcolor-util',
  srcs=[
    'termcolor_util/__init__.py',
  ],
  deps=[
    requirement('termcolor'),
  ],
  imports=[""],
)

py_binary(
  name='termcolor-util-binary',
  srcs=[
    'termcolor_util/__main__.py',
  ],
  deps=[
    ":termcolor-util",
  ],
  main='termcolor_util/__main__.py',
)

py3_image(
  name='termcolor-util-image',
  srcs=[
    'termcolor_util/__main__.py',
  ],
  deps=[
    ":termcolor-util",
  ],
  main='termcolor_util/__main__.py',
)
