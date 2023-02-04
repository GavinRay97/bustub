FROM ubuntu:22.10
CMD bash

# Install Ubuntu packages.
# Please add packages in alphabetical order.
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y \
  build-essential \
  clang-15 \
  clang-format-15 \
  clang-tidy-15 \
  clangd-15 \
  cmake \
  doxygen \
  g++-12 \
  gdb \
  git \
  lld-15 \
  lldb-15 \
  ninja-build \
  pkg-config \
  zlib1g-dev
