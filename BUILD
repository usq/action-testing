
py_library(
    name="foo",
    srcs=["mod.py"]
)

py_test(name="test",
        main="test_mod.py",
        srcs=["test_mod.py"],
        deps=[":foo"])
