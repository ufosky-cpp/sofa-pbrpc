git_repository(
  name = "protobuf",
  remote = "https://github.com/google/protobuf",
  tag = "v3.5.1.1"
)

new_git_repository(
  name = "snappy",
  remote = "https://github.com/google/snappy",
  commit = "32d6d7d8a2ef328a2ee1dd40f072e21f4983ebda", # latest master
  build_file = "bazel/snappy.BUILD"
)

new_git_repository(
  name = "gtest",
  remote = "https://github.com/google/googletest.git",
  tag = "release-1.8.0",
  build_file = "bazel/gtest.BUILD",
)

new_http_archive(
  name = "boost",
  url = "https://sourceforge.net/projects/boost/files/boost/1.66.0/boost_1_66_0.tar.bz2/download",
  type = "tar.bz2",
  strip_prefix = "boost_1_66_0/",
  build_file = "bazel/boost.BUILD",
#  sha256 = "a547bd06c2fd9a71ba1d169d9cf0339da7ebf4753849a8f7d6fdb8feee99b640",
)

new_http_archive(
  name = "zlib",
  url = "https://sourceforge.net/projects/libpng/files/zlib/1.2.11/zlib-1.2.11.tar.gz/download",
  type = "tar.gz",
  build_file = "bazel/zlib.BUILD",
  strip_prefix = "zlib-1.2.11/",
  sha256 = "c3e5e9fdd5004dcb542feda5ee4f0ff0744628baf8ed2dd5d66f8ca1197cb1a1",
)
