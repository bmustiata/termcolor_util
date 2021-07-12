load("@termcolor-util-pip//:requirements.bzl", "requirement")

py_library(
  name='termcolor-util',
  srcs=[
    'termcolor_util/__init__.py',
  ],
  deps=[
    requirement('termcolor'),
  ],
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

