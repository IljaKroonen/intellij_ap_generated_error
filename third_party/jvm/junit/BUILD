licenses(["notice"])
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_import")
java_library(
    name = "junit",
    exports = [
        "//external:jar/junit/junit"
    ],
    runtime_deps = [
        "//third_party/jvm/org/hamcrest:hamcrest_core"
    ],
    visibility = [
        "//third_party/jvm:__subpackages__"
    ]
)


