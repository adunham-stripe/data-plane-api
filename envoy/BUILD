licenses(["notice"])  # Apache 2

# TODO(htuch): Grow this to cover everything we want to generate docs for, so we can just invoke
# bazel build //envoy/api --aspects tools/protodoc/protodoc.bzl%proto_doc_aspect  --output_groups=rst
proto_library(
    name = "envoy",
    deps = [
        "//envoy/api/v2",
        "//envoy/api/v2/cluster",
        "//envoy/api/v2/cluster:circuit_breaker",
        "//envoy/api/v2/cluster:outlier_detection",
        "//envoy/api/v2/filter/accesslog",
        "//envoy/api/v2/filter/http",
        "//envoy/api/v2/filter/network",
        "//envoy/api/v2/listener",
        "//envoy/api/v2/ratelimit",
        "//envoy/api/v2/route",
        "//envoy/config/bootstrap/v2:bootstrap",
        "//envoy/config/metrics/v2:metrics_service",
        "//envoy/config/metrics/v2:stats",
        "//envoy/config/ratelimit/v2:rls",
        "//envoy/config/trace/v2:trace",
        "//envoy/service/discovery",
        "//envoy/service/load_stats",
        "//envoy/service/metrics",
    ],
)
