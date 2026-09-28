---
name: mediaruntime-create-and-retrieve-job
description: Create a new media job, retrieve its details, and list all jobs.
api: openapi/mediaruntime-jobs-api-openapi.yml
operations:
- createJob
- getJob
- listJobs
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mediaruntime-jobs-api-openapi.yml ; every operationId checked against the contract
---

# mediaruntime-create-and-retrieve-job

Create a new media job, retrieve its details, and list all jobs.

## Steps

1. 1. Call `createJob` with the required request body fields for the new job.
2. 2. Call `getJob` with the `job_id` returned from `createJob` to fetch the job details.
3. 3. Call `listJobs` to retrieve a list of all jobs.

## Rules

- Include the ProductionApiKey in the request header `X-API-Key` for authentication.
