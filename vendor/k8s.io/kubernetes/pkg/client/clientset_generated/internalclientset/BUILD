load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "clientset.go",
        "doc.go",
    ],
    importpath = "k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/glog:go_default_library",
        "//vendor/k8s.io/client-go/discovery:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
        "//vendor/k8s.io/client-go/util/flowcontrol:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/admissionregistration/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/apps/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/authentication/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/authorization/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/autoscaling/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/batch/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/certificates/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/core/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/events/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/extensions/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/networking/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/policy/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/rbac/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/scheduling/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/settings/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/storage/internalversion:go_default_library",
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
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/fake:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/scheme:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/admissionregistration/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/apps/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/authentication/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/authorization/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/autoscaling/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/batch/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/certificates/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/core/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/events/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/extensions/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/networking/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/policy/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/rbac/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/scheduling/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/settings/internalversion:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/storage/internalversion:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
