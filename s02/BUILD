

cc_library(
    name = "muduo_reactor",
    srcs = "reactor/*.cc",
    deps = [
        "//common:muduo_common",
    ],
    optimize = ["-O0", "-g", "-Wall"],
)

cc_binary(
    name = "test1",
    srcs = "test1.cc",
    deps = ":muduo_reactor",
    optimize = ["-O0", "-g", "-Wall"],
)

cc_binary(
    name = "test2",
    srcs = "test2.cc",
    deps = ":muduo_reactor",
    optimize = ["-O0", "-g", "-Wall"],
)

cc_binary(
    name = "test3",
    srcs = "test3.cc",
    deps = ":muduo_reactor",
    optimize = ["-O0", "-g", "-Wall"],
)

cc_binary(
    name = "test4",
    srcs = "test4.cc",
    deps = ":muduo_reactor",
    optimize = ["-O0", "-g", "-Wall"],
)
