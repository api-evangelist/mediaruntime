---
name: mediaruntime-fetch-sticker
description: Retrieve a hosted sticker's metadata using a scoped Sticker Runtime client token.
api: openapi/mediaruntime-openapi.json
operations:
- createStickerRuntimeClientToken
- getRuntimeSticker
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mediaruntime-openapi.json ; every operationId checked against the contract
---

# mediaruntime-fetch-sticker

Retrieve a hosted sticker's metadata using a scoped Sticker Runtime client token.

## Steps

1. 1. Obtain a scoped client token with `createStickerRuntimeClientToken` (requires header `X-API-Key` for ProductionApiKey or `X-Sandbox-Token` for SandboxToken).
2. 2. Use the token to call `getRuntimeSticker` (requires header `StickerClientToken` with the token value) and provide the path parameter `sticker_id`.

## Rules

- Auth: Include `X-API-Key` (ProductionApiKey) or `X-Sandbox-Token` (SandboxToken) when creating the client token; subsequent calls use the `StickerClientToken` header with the returned token.
- All requests are made to the server `https://mediaruntime.com`.
