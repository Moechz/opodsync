# Changelog

All notable user-visible changes to the oPodSync TOS application package.

## 0.5.0-1 — 2026-11-12

### Added
- First release. oPodSync (`ganeshlab/opodsync:0.5.0-amd64`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8111 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/opodsyncdocker/`.
