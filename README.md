# Vita Ingest staging Tinfoil config

Dedicated public attestation configuration for the debug
`staging-vita-ingest` enclave.

- Production configuration remains in `VitaDAO/vita-ingest-tinfoil-config`.
- This repository mounts only staging Supabase and PostHog credentials.
- Images are pinned by immutable digest and releases use lightweight tags.
- Secret values belong in the Tinfoil organization vault, never in Git.

Current candidate:

- Vita App PR: [VitaDAO/vita-app#356](https://github.com/VitaDAO/vita-app/pull/356)
- Source: `ea189241aa84eeb621bea509488d03f8d134f32f`
- Image: `ghcr.io/vitadao/vita-ingest:sha-ea18924@sha256:7ac15216a00aa320f72e820a83b767191f9be5d3f5fab442bda8680b1ed1a96e`
