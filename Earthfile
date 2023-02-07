VERSION 0.7
PROJECT jalletto/benchmarks

FROM --platform linux/amd64 debian:testing

build:
  PIPELINE
  TRIGGER manual
  TRIGGER pr master
  TRIGGER push master
  BUILD ./docker+run-base64