VERSION --use-project-secrets --use-pipelines 0.6
PROJECT jalletto/benchmarks

FROM ubuntu:latest

satellite-4-pipeline:
  PIPELINE
  TRIGGER manual
  TRIGGER pr main
  TRIGGER push main
  RUN echo hello Josh
