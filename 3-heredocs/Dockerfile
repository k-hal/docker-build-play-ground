# syntax = docker/dockerfile:1.27-labs
FROM amazonlinux:2023

RUN <<EOF
  yum update -y
  yum install -y git
  yum install -y tree
  yum install -y jq
  yum install -y wget
  rm -rf /var/cache/yum
EOF
