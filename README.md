# PRAXO-CORE for Objective-C

Dedicated repository for the Objective-C implementation of PRAXO-CORE: an
embeddable, MIT-licensed agent execution kernel with policy controls,
human-in-the-loop approval, checkpoints, events, and tool calling.

- Package: `praxo-core-objc` (source build)
- Documentation: https://axisvela.github.io/praxo-core/languages/objc/
- Canonical source: https://github.com/axisvela/praxo-core/tree/main/language/objc
- Release index: https://axisvela.github.io/praxo-core/languages/registry-status/

This repository is a discovery mirror of the canonical Objective-C source. The
monorepo remains the source of truth and the release workflow source. Shared
conformance vectors are included under `spec/`.

CocoaPods publication is pending. Windows GNUstep and macOS CI are recorded in
the canonical repository.

## Build

Build from `language/objc` with the Objective-C compiler and GNUstep or Apple
Foundation.

## Verify

Build and test instructions are in `language/objc/README.md`. The monorepo CI
runs the Objective-C conformance, API snapshot, and native tests.

PRAXO-CORE is not a hosted model, workflow engine, identity provider, or safety
controller. Do not infer exactly-once execution, complete sandbox isolation,
production security certification, live-provider behavior, or physical safety
from this package.

MIT licensed.
