load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "PreferencesTable",
    module_name = "PreferencesTable",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
        "//submodules/Database/ValueBox:ValueBox",
        "//submodules/Database/Table:Table",
        "//submodules/Database/PostboxCoding:PostboxCoding",
        "//submodules/Database/PostboxDataTypes:PostboxDataTypes",
    ],
    visibility = [
        "//visibility:public",
    ],
)
