load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_library")

kt_jvm_library(
    name = "dagger",
    srcs = glob([
        "*.kt",
    ]),
    deps = [
        "//third_party:dagger",
    ],
)

java_binary(
    name = "run",
    runtime_deps = [":dagger"],
    main_class = "com.github.iljakroonen.dagger.ToastKt",
)
