java_test(
    name = "HandleTMasterLocationTest",
    srcs = glob(["**/HandleTMasterLocationTest.java"]),
    deps = [
        "//heron/api/src/java:api-java", 
        "//heron/common/src/java:common-java", 
        "//heron/metricsmgr/src/java:metricsmgr-java", 
        "//heron/proto:proto_common_java",
        "//heron/proto:proto_metrics_java",
        "//heron/proto:proto_tmaster_java",
        "@protobuf-java//jar",
        "@bazel_tools//third_party:mockito",
        "@bazel_tools//third_party:junit4",
    ],
    size = "small",
)

java_test(
    name = "MetricsManagerServerTest",
    srcs = glob(["**/MetricsManagerServerTest.java"]),
    deps = [
        "//heron/api/src/java:api-java", 
        "//heron/common/src/java:common-java", 
        "//heron/spi/src/java:metricsmgr-spi-java", 
        "//heron/metricsmgr/src/java:metricsmgr-java", 
        "//heron/proto:proto_common_java",
        "//heron/proto:proto_metrics_java", 
        "@protobuf-java//jar",
        "@bazel_tools//third_party:junit4",
    ],
    size = "small",
)

java_test(
    name = "SinkExecutorTest",
    srcs = glob(["**/SinkExecutorTest.java"]),
    deps = [
        "//heron/api/src/java:api-java", 
        "//heron/common/src/java:common-java", 
        "//heron/spi/src/java:metricsmgr-spi-java", 
        "//heron/metricsmgr/src/java:metricsmgr-java", 
        "//heron/proto:proto-java",
        "@protobuf-java//jar",
        "@bazel_tools//third_party:junit4",
    ],
    size = "small",
)

java_test(
    name = "TMasterSinkTest",
    srcs = glob(["**/TMasterSinkTest.java"]),
    deps = [
        "//heron/api/src/java:api-java", 
        "//heron/common/src/java:common-java", 
        "//heron/spi/src/java:metricsmgr-spi-java", 
        "//heron/metricsmgr/src/java:metricsmgr-java", 
        "//heron/proto:proto_tmaster_java",
        "@protobuf-java//jar",
        "@bazel_tools//third_party:junit4",
    ],
    size = "small",
)
