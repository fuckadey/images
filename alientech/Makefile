ERLANG_VERSION=27.2
LFE_VERSION=2.1.5

all: local

local:
	podman build -t alientech:latest . --build-arg ERLANG_VERSION=${ERLANG_VERSION} \
                                       --build-arg LFE_VERSION=${LFE_VERSION}
