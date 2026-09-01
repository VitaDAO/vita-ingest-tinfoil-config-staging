# Vita Ingest staging Tinfoil config

Dedicated public attestation configuration for the debug
`staging-vita-ingest` enclave.

- Production configuration remains in `VitaDAO/vita-ingest-tinfoil-config`.
- This repository mounts only staging Supabase and PostHog credentials.
- Images are pinned by immutable digest and releases use lightweight tags.
- Secret values belong in the Tinfoil organization vault, never in Git.

Current source revision:
`10ec6563239d805a82f1852ffabade98598d43b2`.
