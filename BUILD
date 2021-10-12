subinclude("//_build/please:python.plz")

package(default_visibility = ["PUBLIC"])


python_library(
  name="termcolor-util-lib",
  deps=[
    "//_build/thirdparty/python:termcolor",
  ],
  srcs=glob(["termcolor_util/**/*.py"]),
)


ge_python_library(
  name="termcolor-util",
  deps=[
    "//_build/thirdparty/gepython:termcolor",
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

