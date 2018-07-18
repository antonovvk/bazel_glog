git_repository(
    name = "bazel_rules",
    remote = "https://github.com/antonovvk/bazel_rules",
    commit = "92d68c1b116f1d1335c0cf570be5ddf4f5645e5b",
)

new_git_repository(
    name = "glog_repo",
    remote = "https://github.com/google/glog.git",
    tag = "v0.3.5",
    build_file = "glog.BUILD"
)

git_repository(
    name = "googletest",
    remote = "https://github.com/google/googletest",
    commit = "077ee54cefd247656ac9a995e150e0d1ab9d0bf7",
)

bind(
    name = "glog",
    actual = "@glog_repo//:glog"
)

git_repository(
    name = "gflags_repo",
    remote = "https://github.com/gflags/gflags.git",
    tag = "v2.2.0",
)

bind(
    name = "gflags",
    actual = "@gflags_repo//:gflags",
)
