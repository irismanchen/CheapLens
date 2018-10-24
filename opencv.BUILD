cc_library(
    name = "opencv",
    srcs = glob(["lib/*.dylib"]),# for mac
    #srcs = glob(["lib/*.so*"]),
    hdrs = glob(["include/**/*.hpp"] + glob(["include/**/*.h"])),
    includes = ["include"],
    visibility = ["//visibility:public"], 
    linkstatic = 1,
)
