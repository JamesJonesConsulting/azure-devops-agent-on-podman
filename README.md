# Azure DevOps Agents setup backed by Podman replacement for Docker

This pipeline installs one or more agents to a target system based on an array of settings passed into the pipeline. This version
stores that array of values in an Ansible inventory. This pipeline runs inside a podman container with ansible-core and other
'helpful' packages installed suited for automation.

