load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    importpath = "k8s.io/kubernetes/pkg/client/informers/informers_generated/internalversion/certificates",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/kubernetes/pkg/client/informers/informers_generated/internalversion/certificates/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/informers/informers_generated/internalversion/internalinterfaces:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/informers/informers_generated/internalversion/certificates/internalversion:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
