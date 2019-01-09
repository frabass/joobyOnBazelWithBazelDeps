package(default_visibility = ["//visibility:public"])

java_library(
    name = "lib",
    srcs = glob(["src/main/java/com/mycompany/*.java"]),
    deps = [
        "//thirdparty/com/google/inject:guice",
        "//thirdparty/io/netty:netty_transport_native_unix_common",
        "//thirdparty/org/jooby",
        "//thirdparty/org/jooby:funzy",
        "//thirdparty/org/jooby:jooby_netty",
    ],
)

java_binary(
    name = "app",
    main_class = "com.mycompany.App",
    runtime_deps = [":lib"],
)
