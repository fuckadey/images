CLANG_VERSION := 19.1.0
CMAKE_VERSION := 3.31.1
CONAN_VERSION := 2.10.0

all: local

local:
	podman build -t local/clang:latest . --build-arg CLANG_VERSION=${CLANG_VERSION} \
	                                     --build-arg CMAKE_VERSION=${CMAKE_VERSION} \
										 --build-arg CONAN_VERSION=${CONAN_VERSION}
