# ClusterFuzzLite build image for DelegationBench fuzz targets.
# Base image digest pinned for reproducible builds; Dependabot tracks it.
FROM gcr.io/oss-fuzz-base/base-builder-python@sha256:6b2b3a7e4a2da50de47f94925cffbe34747e1aae4f33d7f07ba6c681dd648b23

COPY . $SRC/delegationbench
WORKDIR $SRC/delegationbench
COPY .clusterfuzzlite/build.sh $SRC/build.sh
