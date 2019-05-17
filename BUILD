package(default_visibility = ["//visibility:public"])
load("//:hello.bzl", "hello")

# Generates a Java source file that says "Hello John!".
hello(
    name = "hello",
    firstname = "Karthik",
)

java_binary(
    name = "helloworld_bin",
    srcs = [
        ":hello",  # a generates .java file
    ],
    main_class = "bazel.examples.helloworld.hello",
)
