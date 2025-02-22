---
title: Miscellaneous Troubleshooting
---
### Restarting the container when using SQLite drops all the data/requires a full re-scan

Verify that the database is mapped to a persistent storage volume in your docker compose or Unraid template.

```
    "/path/to/database:/romm/database" # [Optional] Only needed if ROMM_DB_DRIVER=sqlite or not set
```

### Error: `Could not get twitch auth token: check client_id and client_secret`

This is likely due to misconfigured environment variables; verify that `CLIENT_ID` and `CLIENT_SECRET` are set correctly, and that both match the values in IGDB.
