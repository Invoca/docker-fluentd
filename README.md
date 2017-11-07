# docker-fluentd

Full source at:
  https://github.com/fluent/fluentd-kubernetes-daemonset/tree/master/docker-image/v0.12/debian-s3

Changes:
  Adds following plugin to list of installed plugins in Dockerfile
    - fluent-plugin-concat
    - fluent-plugin-elasticsearch
