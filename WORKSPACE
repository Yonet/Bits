load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
  name = "jazelle",
  url = "https://registry.yarnpkg.com/jazelle/-/jazelle-0.0.0-alpha.2.tgz",
  strip_prefix = "package",
)

load("@jazelle//:workspace-rules.bzl", "jazelle_dependencies")
jazelle_dependencies(
  node_version = "12.16.1",
  node_sha256 = {
    "mac": "e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855",
    "linux": "",
    "windows": "",
  },
  yarn_version = "1.22.0",
  yarn_sha256 = "",
)
