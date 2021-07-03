
python_library(
    name="termcolor_util",
    srcs=glob(["termcolor_util/__init__.py"]),
    deps=["//thirdparty/python:termcolor"],
)

python_binary(
    name="termcolor_util_main",
    deps=[":termcolor_util"],
    main="termcolor_util/__main__.py",
)

