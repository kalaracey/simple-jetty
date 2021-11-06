load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "server",
    srcs = ["Main.java"],
    deps = [
                "@maven//:org_eclipse_jetty_jetty_server",
                "@maven//:org_eclipse_jetty_jetty_servlet",
                "@maven//:javax_servlet_javax_servlet_api"
    ]
)