# CHANGELOG


## v0.1.0 (2024-10-15)

### Chores

* chore(pyproject.toml): comment out repo_dir to avoid hardcoding local path and improve portability ([`255ca5d`](https://github.com/aspatari/semver-playground-python/commit/255ca5d2908572a5ae613ed5972dee2509f9f600))

* chore(ci): update CI workflow to use semantic-release for versioning and changelog generation
feat(changelog): add CHANGELOG.md to track project changes and versions
fix(pyproject.toml): correct version format from v0.1.0 to 0.1.0 for semantic versioning compliance
refactor(pyproject.toml): comment out unused semantic release configurations to simplify setup
fix(version.py): ensure version information is consistent with semantic versioning standards ([`f8e15b5`](https://github.com/aspatari/semver-playground-python/commit/f8e15b5a8a145a72b228ff1ecbf94267ce1ed5e2))

* chore(pyproject.toml): update semantic release configuration to enhance versioning and changelog generation process ([`08d3da0`](https://github.com/aspatari/semver-playground-python/commit/08d3da08f54e176185792a3fc82beac68d7cab17))

* chore(pyproject.toml): update version format from 0.1.0 to v0.1.0 to align with semantic versioning conventions ([`ce1670f`](https://github.com/aspatari/semver-playground-python/commit/ce1670fb350117baa1fdbff74f0e5406c786918f))

* chore(pyproject.toml): update configuration to set branch to main and enable upload to release
feat(pyproject.toml): add build_command to streamline the build process with poetry ([`be24fdf`](https://github.com/aspatari/semver-playground-python/commit/be24fdfef60629ae6e4483b95f07b0cad40fbe84))

* chore(ci): comment out conditional for Release job to prevent premature execution during pushes to master ([`9204918`](https://github.com/aspatari/semver-playground-python/commit/92049188ef21dcf48b7fafe745d3e443aae549f1))

### Features

* feat(pyproject.toml): add version_toml configuration for semantic release to track version in pyproject.toml and version.py
feat(version.py): create version module to store version information and prevent manual edits ([`1d5fa8b`](https://github.com/aspatari/semver-playground-python/commit/1d5fa8badf3e8d7083cbb96d8997e972385fb0b7))

### Fixes

* fix(pyproject.toml): update version_toml configuration to use pyproject.toml for versioning to ensure consistency in version management ([`b3ad54f`](https://github.com/aspatari/semver-playground-python/commit/b3ad54ff66cf649fb830934e0863e1419588d42c))

### Unknown

* chore(release):1.1.1 ([`9809f59`](https://github.com/aspatari/semver-playground-python/commit/9809f594d57798ed66e2c7c51acb56d321cb65ad))

* redeploy ([`3702ce4`](https://github.com/aspatari/semver-playground-python/commit/3702ce424ef86217a9d60a40a5ec804539229210))

* Initial commit ([`ae5d7a2`](https://github.com/aspatari/semver-playground-python/commit/ae5d7a20fedd99e5f571099c92ed8326d892d6a6))
