load("@io_bazel_rules_scala//scala_proto:scala_proto.bzl", "scala_proto_library")

scala_proto_library(
    name = "protobuf",
    deps = [":compression_proto"],
)

proto_library(
    name = "compression_proto",
    srcs = ["compression.proto"],
)
