java_library(
    name = "netty_buffer",
    exports = [
        "//external:jar/io/netty/netty_buffer"
    ],
    runtime_deps = [
        ":netty_common"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_codec",
    exports = [
        "//external:jar/io/netty/netty_codec"
    ],
    runtime_deps = [
        ":netty_transport"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_codec_http",
    exports = [
        "//external:jar/io/netty/netty_codec_http"
    ],
    runtime_deps = [
        ":netty_codec"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_codec_http2",
    exports = [
        "//external:jar/io/netty/netty_codec_http2"
    ],
    runtime_deps = [
        ":netty_codec_http",
        ":netty_handler"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_common",
    exports = [
        "//external:jar/io/netty/netty_common"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_handler",
    exports = [
        "//external:jar/io/netty/netty_handler"
    ],
    runtime_deps = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_transport"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_resolver",
    exports = [
        "//external:jar/io/netty/netty_resolver"
    ],
    runtime_deps = [
        ":netty_common"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_tcnative_boringssl_static_jar_linux_x86_64",
    exports = [
        "//external:jar/io/netty/netty_tcnative_boringssl_static_jar_linux_x86_64"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_transport",
    exports = [
        "//external:jar/io/netty/netty_transport"
    ],
    runtime_deps = [
        ":netty_buffer",
        ":netty_resolver"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_transport_native_epoll_jar_linux_x86_64",
    exports = [
        "//external:jar/io/netty/netty_transport_native_epoll_jar_linux_x86_64"
    ],
    runtime_deps = [
        ":netty_buffer",
        ":netty_common",
        ":netty_transport"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "netty_transport_native_unix_common",
    exports = [
        "//external:jar/io/netty/netty_transport_native_unix_common"
    ],
    runtime_deps = [
        ":netty_common",
        ":netty_transport"
    ],
    visibility = [
        "//visibility:public"
    ]
)


