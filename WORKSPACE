load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

rules_kotlin_version = "cab5eaffc2012dfe46260c03d6419c0d2fa10be0"

http_archive(
    name = "io_bazel_rules_kotlin",
    urls = ["https://github.com/bazelbuild/rules_kotlin/archive/%s.zip" % rules_kotlin_version],
    type = "zip",
    strip_prefix = "rules_kotlin-%s" % rules_kotlin_version
)

load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kotlin_repositories", "kt_register_toolchains")
kotlin_repositories()
kt_register_toolchains()

http_jar(
    name = "bazel_deps",
    sha256 = "fd27227dd47bd3fb0e1bca912167d20e4655845a2af4f162de682ec6a3babc83",
    url = "https://github.com/IljaKroonen/artifacts/blob/00d758907f5e6649aa42566d324b6f11e496b3e2/parseproject_deploy_1af8921d52f053fad575f26762533a3823b4a847.jar?raw=true",
)

load("//third_party/jvm:workspace.bzl", "maven_dependencies")

maven_dependencies()
