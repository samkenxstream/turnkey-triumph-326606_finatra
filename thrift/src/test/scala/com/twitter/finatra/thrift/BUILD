scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "finatra-thrift-tests",
        repo = artifactory,
    ),
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/com/google/inject/extensions:guice-testlib",
        "3rdparty/jvm/net/codingwell:scala-guice",
        "3rdparty/jvm/org/scalatest",
        "finagle/finagle-core/src/main",
        "finagle/finagle-thriftmux/src/main/scala",
        "finatra/inject/inject-ports/src/main/scala/com/twitter/inject/server",
        "finatra/inject/inject-server/src/main/scala/com/twitter/inject/server",
        "finatra/inject/inject-server/src/test/scala/com/twitter/inject/server",
        "scrooge/scrooge-core/src/main/scala",
        "twitter-server/server/src/main/scala",
        "util/util-stats/src/main/scala",
    ],
    exports = [
        "3rdparty/jvm/net/codingwell:scala-guice",
    ],
)
