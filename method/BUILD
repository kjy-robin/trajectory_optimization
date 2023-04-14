load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

cc_binary(
	name = "main",
	srcs = ["main.cc"],
	deps = [":lqr",],
)

cc_library(
  name = "lqr",
  srcs = ["lqr.cc"],
	hdrs = ["lqr.h"],
)
