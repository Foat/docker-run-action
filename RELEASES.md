# frozen-tapestry/docker-run-action Releases

### v6.0.0

- Migrated to Node.js implementation. Action runs via `node20` environment.
- Added `socket` input for specifying Docker socket path.
- Improved workspace mounting logic.
- Enhanced signal handling for old podman versions.
- Added bash strict mode.

### v5.0.0: Workspace Mount Support

- Added `mount_ws` parameter for workspace mounting, compatible with GitHub and Gitea.
- New tests for verifying automatic and custom directory mounting.
- Enhanced `entrypoint.sh` for flexible mounts and updated documentation examples.

### v4.0.0

- Added [Gitea Actions](https://docs.gitea.com/next/usage/actions/overview) support.
- Versions upgrade.

# addnab/docker-run-action Releases

### 3.0.0

- Upgrade to docker 20.10 https://github.com/addnab/docker-run-action/pull/12

### 2.0.0

- Added support for networking with other containers [#3](https://github.com/addnab/docker-run-action/pull/3) [#7](https://github.com/addnab/docker-run-action/pull/7)
- Added tests [#7](https://github.com/addnab/docker-run-action/pull/7)

### 1.0.0

- Initial release
