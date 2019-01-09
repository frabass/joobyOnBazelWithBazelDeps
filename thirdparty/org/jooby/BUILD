java_library(
    name = "funzy",
    exports = [
        "//external:jar/org/jooby/funzy"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "jooby",
    exports = [
        "//external:jar/org/jooby/jooby"
    ],
    runtime_deps = [
        "//thirdparty/ch/qos/logback:logback_classic",
        "//thirdparty/com/google/guava:guava",
        "//thirdparty/com/google/inject/extensions:guice_multibindings",
        "//thirdparty/com/typesafe:config",
        "//thirdparty/org/slf4j:slf4j_api",
        ":funzy"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "jooby_netty",
    exports = [
        "//external:jar/org/jooby/jooby_netty"
    ],
    runtime_deps = [
        "//thirdparty/io/netty:netty_codec",
        "//thirdparty/io/netty:netty_codec_http",
        "//thirdparty/io/netty:netty_codec_http2",
        "//thirdparty/io/netty:netty_common",
        "//thirdparty/io/netty:netty_handler",
        "//thirdparty/io/netty:netty_resolver",
        "//thirdparty/io/netty:netty_tcnative_boringssl_static_jar_linux_x86_64",
        "//thirdparty/io/netty:netty_transport",
        "//thirdparty/io/netty:netty_transport_native_epoll_jar_linux_x86_64",
        "//thirdparty/org/javassist:javassist",
        ":jooby"
    ],
    visibility = [
        "//visibility:public"
    ]
)


