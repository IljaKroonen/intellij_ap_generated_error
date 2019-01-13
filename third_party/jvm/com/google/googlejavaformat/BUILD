licenses(["notice"])
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_import")
java_library(
    name = "google_java_format",
    exports = [
        "//external:jar/com/google/googlejavaformat/google_java_format"
    ],
    runtime_deps = [
        "//third_party/jvm/com/google/errorprone:javac_shaded",
        "//third_party/jvm/com/google/guava:guava"
    ],
    visibility = [
        "//third_party/jvm:__subpackages__"
    ]
)


