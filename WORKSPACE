#
# Copyright (c) 2019 Stackinsights to present
# All rights reserved
#

workspace(name = "stackinsights_data_collect_protocol")

load("//bazel:repositories.bzl", "stackinsights_data_collect_protocol_dependencies")

stackinsights_data_collect_protocol_dependencies()

load("@rules_proto//proto:repositories.bzl", "rules_proto_dependencies", "rules_proto_toolchains")

rules_proto_dependencies()

rules_proto_toolchains()

load("@com_github_grpc_grpc//bazel:grpc_deps.bzl", "grpc_deps")

grpc_deps()

load("@com_github_grpc_grpc//bazel:grpc_extra_deps.bzl", "grpc_extra_deps")

grpc_extra_deps()
