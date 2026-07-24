# ClusterFuzzLite build image for DelegationBench fuzz targets.
# Base image digest pinned for reproducible builds; Dependabot tracks it.
FROM gcr.io/oss-fuzz-base/base-builder-python@sha256:3cb899359c06448afeabcffeefa9b814acb5040e391757a5790cdaa7d05ec520

COPY . $SRC/delegationbench
WORKDIR $SRC/delegationbench
COPY .clusterfuzzlite/build.sh $SRC/build.sh
