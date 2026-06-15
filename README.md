## 🔒 Commercial Integrity & Verification

To protect our intellectual property while ensuring maximum security for enterprise ingestion pipelines, the core production-ready C++ engine (`safemark.hpp`) remains in a private repository for licensed clients.

However, the integrity of the release is fully verifiable. You can audit the cryptographic thumbprint of the source code via our public SHA-256 manifest:

* **Release Manifest:** [safemark.hpp.sha256](./safemark.hpp.sha256)
* **Expected Hash:** `9aefca12bd873d9e8b368c5b08e2f3d17c92b2361df4b5e28a5d3c87e6015b74`

Licensed users can run `sha256sum -c safemark.hpp.sha256` upon integration to verify they are running the official, untampered parser protection layer.
