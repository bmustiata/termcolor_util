subinclude("//build/please:python.plz")


ge_python_library(
  name="termcolor-util",
  deps=[
    "//build/thirdparty/python:termcolor",
  ],
  srcs=glob(["termcolor_util/**/*.py"]),
)


ge_python_image(
  name="termcolor-util-image",
  deps=[
    ":termcolor-util",
  ],
  main="termcolor_util/__main__.py",
)

