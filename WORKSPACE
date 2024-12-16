workspace(name = "bazel_rust_example")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_rust",
    sha256 = "6357de5996a20e48ef84c493bfc0e5d08ea1d291fd4468f49576c54cd024dcb4",
    urls = ["https://github.com/bazelbuild/rules_rust/releases/download/0.37.0/rules_rust-v0.37.0.tar.gz"],
)

load("@rules_rust//rust:repositories.bzl", "rules_rust_dependencies", "rust_register_toolchains")

rules_rust_dependencies()
rust_register_toolchains()
