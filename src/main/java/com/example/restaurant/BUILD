java_library(
    name = "cafe",
    srcs = [
        "Cafe.java",
        "Chef.java",
    ],
    deps = [
        ":chef",
    ],
)

java_library(
    name = "chef",
    srcs = [
        "Chef.java",
        "src/main/java/com/example/dishes/MacAndCheese.java",
        "src/main/java/com/example/dishes/Pizza.java",
    ],
    deps = [
        "//dishes:macAndCheese",
        "//dishes:pizza",
    ],
)