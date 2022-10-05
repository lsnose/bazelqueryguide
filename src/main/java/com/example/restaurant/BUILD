java_library(
    name = "chef",
    srcs = [
        "Chef.java",
        "dishes/MacAndCheese.java",
        "dishes/Pizza.java",
    ],
    deps = [
        "//src/main/java/com/example/dishes:macAndCheese",
        "//src/main/java/com/example/dishes:pizza",
    ],

)

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
