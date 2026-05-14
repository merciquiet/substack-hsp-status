# substack-hsp-status

Status snapshot file mirror for a scheduled automation system.

## Purpose

A scheduled automation fetches `status.json` from this repository via raw URL to evaluate alert conditions:

```
https://raw.githubusercontent.com/merciquiet/substack-hsp-status/main/status.json
```

## Update flow

`status.json` is updated periodically by upstream tooling. Commits are made by an anonymized identity.
