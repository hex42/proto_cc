load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
        name="grpc",
        remote="https://github.com/grpc/grpc.git",
        commit="e73882dc0fcedab1ffe789e44ed6254819639ce3",
)

load("@grpc//bazel:grpc_deps.bzl", "grpc_deps")

grpc_deps()
