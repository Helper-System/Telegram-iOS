
objc_library(
    name = "DeviceProximity",
    enable_modules = True,
    module_name = "DeviceProximity",
    srcs = glob([
        "Sources/*.m",
    ]),
    hdrs = glob([
        "PublicHeaders/**/*.h",
    ]),
    includes = [
        "PublicHeaders",
    ],
    sdk_frameworks = [
      "Foundation",
      "UIKit",
    ],
    visibility = [
        "//visibility:public",
    ],
)
