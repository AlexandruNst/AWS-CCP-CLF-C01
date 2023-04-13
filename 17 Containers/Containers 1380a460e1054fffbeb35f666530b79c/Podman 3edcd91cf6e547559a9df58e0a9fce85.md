# Podman

Container engine that is OCI-compliant and is a drop-in replacement for Docker

- Is daemon-less (unlike Docker)
- Allows you to create pods like in K8s (Docker doesn’t)
- Replaces only part of Docker. Needs to be used alongside:
    - **Buildah** - tool used to build the OCI images
    - **Skopeo** - tool for moving container images between different types of container storages

Not gonna show up on exam :)