# Vita Ingest staging Tinfoil config

Dedicated public attestation configuration for the debug
`staging-vita-ingest` enclave.

- Production configuration remains in `VitaDAO/vita-ingest-tinfoil-config`.
- This repository mounts only staging Supabase and PostHog credentials.
- Images are pinned by immutable digest and releases use lightweight tags.
- Secret values belong in the Tinfoil organization vault, never in Git.

Current source revision:
`031414e6e6a7a43f1ac9e0aaf797462c457bcbfb`.

Verified equivalent Vita App staging commit:
`dfb1ce7a2cb6f36cdcf19deb2285540905b3e692`.
