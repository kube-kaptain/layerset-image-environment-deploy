# Layerset Image Environment Deploy

Kaptain layerset composing the full build configuration for image-environment-deploy images.

Composes these layers in order:

1. **layer-github-flow-strict** — strict GitHub flow quality enforcement (slash blocking, conventional commit blocking)
2. **layer-image-environment-deploy** — multi-arch docker builds, compound versioning, post-build validation, additional release branches
