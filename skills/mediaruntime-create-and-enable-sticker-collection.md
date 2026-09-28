---
name: mediaruntime-create-and-enable-sticker-collection
description: Create a new sticker collection and enable a pack within it.
api: openapi/mediaruntime-openapi.json
operations:
- createStickerCollection
- enableStickerCollectionPack
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mediaruntime-openapi.json ; every operationId checked against the contract
---

# mediaruntime-create-and-enable-sticker-collection

Create a new sticker collection and enable a pack within it.

## Steps

1. 1. Call `createStickerCollection` with the required request body fields for the new collection.
2. 2. Call `enableStickerCollectionPack` providing `collection_id` from the previous response and `pack_id` of the pack to enable.

## Rules

- Include the appropriate authentication header (e.g., `X-API-Key` for ProductionApiKey or `X-Sandbox-Token` for SandboxToken).
- Use idempotent HTTP methods where applicable; `PUT` on `enableStickerCollectionPack` is idempotent.
