load("@rules_java//java:defs.bzl", "java_binary", "java_library")

java_binary(
    name = "runner",
    srcs = [
        "//restaurant/Cafe.java",
        "//example/Runner.java",
    ],
    main_class = "com.example.Runner",
    deps = ["//restaurant:cafe"]
)
