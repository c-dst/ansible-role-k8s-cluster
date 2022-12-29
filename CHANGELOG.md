# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/fr/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Role k8s_cni
- Role k8s_cluster

## 0.0.3 - 20221-12-29

### Changed

- Role k8s_cri :
  - Update defaults, vars and syntax

## 0.0.2 - 20221-12-23

### Changed / Fixed

- Role k8s_cri :
  - Update default vars and syntax
  - containerd :
    - update download and install
  - cri-o :
    - update highest kubernetes supported version
    - update apt package source list

## 0.0.1 - 20221-12-22

### Added

- Role k8s_cri : manage Container Runtime Interface for Kubernetes
  Available CRI containerd / cri-o
