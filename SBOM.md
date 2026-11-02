# Source SBOM

**Initial source snapshot, not a release report.** Source commit `d998fad154d3e6ad2d73af5add49beec0d2ab59f` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/pySSTV `d998fad154d3e6ad2d73af5add49beec0d2ab59f`

- sbom:role: source-root
- sbom:git-commit: d998fad154d3e6ad2d73af5add49beec0d2ab59f
- sbom:git-tree: 94533e80e07a68973bc6201786e3c7c6b79fcd2a
- sbom:source-repository: https://github.com/wave-owl/pySSTV
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE.txt", "sha256": "dd04ede42aec9ae526e6eacb8dd8319366878fd4ff2ab780049cc379f7ed7107"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/pySSTV | d998fad154d3e6ad2d73af5add49beec0d2ab59f | source-root | unresolved; manual review required |
| Conditional source requirements declared by pyproject.toml | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by requirements.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by setup.py | unresolved | conditional-build-runtime-requirement | unresolved |
| Pillow==12.3.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| setuptools build backend | unresolved | conditional-build-runtime-requirement | unresolved |
| dev mock==1.0.1 and nose==1.3.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| uv.lock | unresolved | conditional-build-runtime-requirement | unresolved |
| actions/checkout | v3 | Syft source/package discovery | unresolved |
| actions/setup-python | v3 | Syft source/package discovery | unresolved |
| mock | 1.0.1 | Syft source/package discovery | unresolved |
| mock | 1.0.1 | Syft source/package discovery | unresolved |
| nose | 1.3.0 | Syft source/package discovery | unresolved |
| nose | 1.3.0 | Syft source/package discovery | unresolved |
| pillow | 12.3.0 | Syft source/package discovery | unresolved |
| pillow | 12.3.0 | Syft source/package discovery | unresolved |
| pysstv | 0.5.9 | Syft source/package discovery | unresolved |
| /Users/gerolfziegenhain/src/wave-owl/local/sbom-upstream-results/pySSTV/.source-input/.github/workflows/python-package.yml | unresolved | Syft source/package discovery | unresolved |
| /Users/gerolfziegenhain/src/wave-owl/local/sbom-upstream-results/pySSTV/.source-input/requirements.txt | unresolved | Syft source/package discovery | unresolved |
| /Users/gerolfziegenhain/src/wave-owl/local/sbom-upstream-results/pySSTV/.source-input/uv.lock | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
