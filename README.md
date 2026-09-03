# Vita Ingest staging Tinfoil config

Dedicated public attestation configuration for the debug
`staging-vita-ingest` enclave.

- Production configuration remains in `VitaDAO/vita-ingest-tinfoil-config`.
- This repository mounts only staging Supabase and PostHog credentials.
- Images are pinned by immutable digest and releases use lightweight tags.
- Secret values belong in the Tinfoil organization vault, never in Git.

Current candidate:

- Vita App PR: [VitaDAO/vita-app#356](https://github.com/VitaDAO/vita-app/pull/356)
- Source: `a2b6f4a3eafe43b27ba4a7f72c79d48829a3ef65`
- Image: `ghcr.io/vitadao/vita-ingest:sha-a2b6f4a@sha256:22a50ed8a67e15485c4e464d62c791e586251169ff7e7ef3c7acde647ac3494a`
