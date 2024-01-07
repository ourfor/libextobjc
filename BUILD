objc_library(
    name = "libextobjc",
    srcs = glob(["extobjc/*.m", "extobjc/*.mm"]),
    hdrs = glob(["extobjc/*.h"]),
    pch = "extobjc/extobjc_Prefix.pch",
    includes = [
        "extobjc"
    ],
    enable_modules = True,
    visibility = ["//visibility:public"],
)