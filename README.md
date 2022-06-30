# docker-mimir

## Role Variables

```yml
mimir_version: 2.1.0
mimir_host: mimir.example.com
mimir_storage: gcs
mimir_bucket: mimir.example.com
mimir_multitenancy: true
mimir_compactor_block_ranges: 2h0m0s,12h0m0s,24h0m0s
mimir_compactor_compaction_interval: 1h
mimir_unuse_iam: true
```
