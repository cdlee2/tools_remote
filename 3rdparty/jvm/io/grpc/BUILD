java_library(
    name = "grpc_all",
    exports = [
        "//external:jar/io/grpc/grpc_all"
    ],
    runtime_deps = [
        ":grpc_auth",
        ":grpc_context",
        ":grpc_core",
        ":grpc_netty",
        ":grpc_okhttp",
        ":grpc_protobuf",
        ":grpc_protobuf_nano",
        ":grpc_stub",
        ":grpc_testing"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_auth",
    exports = [
        "//external:jar/io/grpc/grpc_auth"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/auth:google_auth_library_credentials"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_context",
    exports = [
        "//external:jar/io/grpc/grpc_context"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_core",
    exports = [
        "//external:jar/io/grpc/grpc_core"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/code/findbugs:jsr305",
        "//3rdparty/jvm/com/google/errorprone:error_prone_annotations",
        "//3rdparty/jvm/com/google/guava:guava",
        "//3rdparty/jvm/com/google/instrumentation:instrumentation_api",
        "//3rdparty/jvm/io/opencensus:opencensus_api",
        "//3rdparty/jvm/io/opencensus:opencensus_contrib_grpc_metrics"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_netty",
    exports = [
        "//external:jar/io/grpc/grpc_netty"
    ],
    runtime_deps = [
        "//3rdparty/jvm/io/netty:netty_codec_http2",
        "//3rdparty/jvm/io/netty:netty_handler_proxy"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_okhttp",
    exports = [
        "//external:jar/io/grpc/grpc_okhttp"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/squareup/okhttp:okhttp",
        "//3rdparty/jvm/com/squareup/okio:okio"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_protobuf",
    exports = [
        "//external:jar/io/grpc/grpc_protobuf"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/api/grpc:proto_google_common_protos",
        "//3rdparty/jvm/com/google/protobuf:protobuf_java",
        "//3rdparty/jvm/com/google/protobuf:protobuf_java_util",
        ":grpc_protobuf_lite"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_protobuf_lite",
    exports = [
        "//external:jar/io/grpc/grpc_protobuf_lite"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_protobuf_nano",
    exports = [
        "//external:jar/io/grpc/grpc_protobuf_nano"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/protobuf/nano:protobuf_javanano"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_stub",
    exports = [
        "//external:jar/io/grpc/grpc_stub"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "grpc_testing",
    exports = [
        "//external:jar/io/grpc/grpc_testing"
    ],
    runtime_deps = [
        "//3rdparty/jvm/junit:junit",
        "//3rdparty/jvm/org/mockito:mockito_core"
    ],
    visibility = [
        "//visibility:public"
    ]
)


