# IPSY CSS backups

Backups of the custom CSS on IPSY's four live TrueLoyal stores (US and MX, prod and staging). Each environment has its own folder with one `custom.css`. A new backup overwrites that file, so the git history is the record of what changed and when.

## Layout

```text
MX-prod/custom.css
MX-staging/custom.css
US-prod/custom.css      (not yet captured, see below)
US-staging/custom.css
```

## Backup log

| Date | Envs captured | Notes |
|------|---------------|-------|
| 2026-10-12 | MX-prod, MX-staging, US-staging | US-prod capture came back empty (0 bytes), so it was left out. It needs to be re-captured. |

Only CSS goes in this repo. The JS backups stay local.
