FROM ubuntu:latest
LABEL authors="iejohnson"

COPY Orthanc /Orthanc
COPY OrthancConfig.json /OrthancConfig.json

ENTRYPOINT ["./run_orthanc.sh"]