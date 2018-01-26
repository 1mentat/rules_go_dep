workspace(name = "rules_go_dep")

# ================================================================

http_archive(
    name = "io_bazel_rules_go",
    sha256 = "4d8d6244320dd751590f9100cf39fd7a4b75cd901e1f3ffdfd6f048328883695",
    url = "https://github.com/bazelbuild/rules_go/releases/download/0.9.0/rules_go-0.9.0.tar.gz",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains", "go_repository")

go_rules_dependencies()

go_register_toolchains()

load("@io_bazel_rules_go//go:def.bzl", "go_repository")

go_repository(
    name = "com_github_BurntSushi_toml",
    commit = "a368813c5e648fee92e5f6c30e3944ff9d5e8895",
    importpath = "github.com/BurntSushi/toml",
)

go_repository(
    name = "org_golang_x_tools_go_vcs",
    commit = "25101aadb97aa42907eee6a238d6d26a6cb3c756",
    importpath = "golang.org/x/tools/go/vcs",
)
