licenses(["notice"])
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_import")
java_library(
    name = "guava",
    exports = [
        "//external:jar/com/google/guava/guava"
    ],
    runtime_deps = [
        "//third_party/jvm/com/google/code/findbugs:jsr305",
        "//third_party/jvm/com/google/errorprone:error_prone_annotations",
        "//third_party/jvm/com/google/j2objc:j2objc_annotations",
        "//third_party/jvm/org/checkerframework:checker_compat_qual",
        "//third_party/jvm/org/codehaus/mojo:animal_sniffer_annotations"
    ],
    visibility = [
        "//third_party/jvm:__subpackages__"
    ]
)


