
ROOT=../..
MK.pyver:=3
include $(ROOT)/deps/readies/mk/main

# OSNICK=buster|stretch|bionic|xenial|centos7
OSNICK ?= buster

REPO=redismodule-rs

REDIS_VER=6.2.2

INT_BRANCHES=

ART_DIR=$(ROOT)/bin/artifacts
ART_INT_DIR=/var/opt/redislabs/artifacts

include $(MK)/docker.native
