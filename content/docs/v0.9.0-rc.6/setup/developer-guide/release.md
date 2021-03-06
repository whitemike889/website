---
title: Release | Stash
description: Stash Release
menu:
  docs_v0.9.0-rc.6:
    identifier: release
    name: Release
    parent: developer-guide
    weight: 15
product_name: stash
menu_name: docs_v0.9.0-rc.6
section_menu_id: setup
info:
  catalog: v0.3.0
  cli: v0.3.1
  version: v0.9.0-rc.6
---

# Release Process

The following steps must be done from a Linux x64 bit machine.

- Do a global replacement of tags so that docs point to the next release.
- Push changes to the `release-x` branch and apply new tag.
- Push all the changes to remote repo.
- Build and push stash docker image:
```console
$ cd ~/go/src/stash.appscode.dev/stash
./hack/docker/setup.sh; env APPSCODE_ENV=prod ./hack/docker/setup.sh release
```

- Now, update the release notes in Github. See previous release notes to get an idea what to include there.
