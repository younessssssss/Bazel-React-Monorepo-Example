load("@aspect_rules_js//js:defs.bzl", "js_library")

ASSET_PATTERNS = [
    "*.svg",
    "*.css",
    "*.js",
]

js_library(
    name = "src",
    srcs = glob(ASSET_PATTERNS),
    visibility = ["//visibility:public"],
)
