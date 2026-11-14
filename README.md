# PRAXO-CORE for Objective-C

Dedicated repository for the Objective-C implementation of PRAXO-CORE: an
embeddable, MIT-licensed agent execution kernel with policy controls,
human-in-the-loop approval, checkpoints, events, and tool calling.

- Package: `praxo-core-objc` (`0.1.1`)
- Registry: Source
- Install: `See README/SETUP.md`
- Documentation: https://axisvela.github.io/praxo-core/languages/objc/
- Examples: https://github.com/axisvela/praxo-core-objc/tree/main/language/objc/examples
- Mirror repository: https://github.com/axisvela/praxo-core-objc
- Canonical source: https://github.com/axisvela/praxo-core/tree/main/language/objc
- Release index: https://axisvela.github.io/praxo-core/languages/registry-status/

This repository is a discovery mirror of the canonical Objective-C source.
The monorepo remains the source of truth and the release workflow source. Shared
conformance vectors are included under `spec/`, so the implementation can be
built and tested here.

## Verify

Build and test instructions are in `language/objc/README.md`. The
monorepo CI runs the language's conformance, API snapshot, and native tests.

PRAXO-CORE is not a hosted model, workflow engine, identity provider, or safety
controller. Do not infer exactly-once execution, complete sandbox isolation,
production security certification, live-provider behavior, or physical safety
from this package.

MIT licensed.
