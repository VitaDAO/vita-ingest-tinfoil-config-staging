# Vita Ingest staging Tinfoil config

Dedicated public attestation configuration for the debug
`staging-vita-ingest` enclave.

- Production configuration remains in `VitaDAO/vita-ingest-tinfoil-config`.
- This repository mounts only staging Supabase and PostHog credentials.
- Images are pinned by immutable digest and releases use lightweight tags.
- Secret values belong in the Tinfoil organization vault, never in Git.

Current source revision:
`c0404c5a80f07bdb39a4d735f0767b44cf7ccdf9`.
