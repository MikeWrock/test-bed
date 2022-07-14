# syntax = docker/dockerfile:1.3

ARG ROS_DISTRO=rolling
ARG BASE_BRANCH=

FROM scratch as base
COPY hello /
CMD ["/hello"]


FROM ghcr.io/mikewrock/test-bed:${ROS_DISTRO}${BASE_BRANCH} as hello_world_image


COPY ignore /
COPY another_file /