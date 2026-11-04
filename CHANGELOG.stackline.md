# Stackline changelog

## 1.0.5 - 2026-11-04

- Make npm select the Stackline README by giving upstream documentation a distinct filename.
- Check the README selected by the actual npm publication parser before release.

## 1.0.4 - 2026-11-04

- Publish the Stackline README with the correct package version.
- Preserve the original upstream README separately; runtime files remain unchanged.
- Verify the README inside the exact npm artifact before publication.

## 1.0.3

- Update the test and lint toolchain, use the maintained Browserify watcher, and remove the unused legacy Coveralls uploader with vulnerable dependencies. Preserve the runtime payload and Node/browser tests.
- Publish accurate development dependency metadata and use patched Node.js 24.22.2 in CI.

## 1.0.0

- Adopt maintenance from `debug@4.4.3` with preserved source history and license.
- Maintenance adoption with preserved runtime payload. No runtime defect correction is claimed. Reports remain visible for subsequent targeted reproduction.
- Add tested, reproducible artifact publication with npm provenance and immutable release evidence.
