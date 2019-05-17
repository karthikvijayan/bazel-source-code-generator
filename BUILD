package(default_visibility = ["//visibility:public"])
load("//:hello.bzl", "hello")

# Generates a Java source file that says "Hello John!".
hello(
    name = "hello",
    firstname = "Karthik",
)

#java_library(
#    name = "hello_java_lib",
#    srcs = glob(["*.java"]),
#)

#java_binary(
#    name = "hello_java_bin",
#    srcs = glob([":hello",]),

#    main_class = "hello",
#    #runtime_deps = [":hello_java_lib"],
#)
