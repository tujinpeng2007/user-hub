# TJP User Hub

This repository contains only the distributable user edition of TJP User Hub.

## Privacy boundary

- `index_to_user.html` is the editable distributable source.
- `dist/index.html` is the Surge deployment entry point.
- The private local `index.html`, backups, editor state, and local history are intentionally ignored and are never part of this repository or deployment.

## Deploy

```bash
npx surge ./dist your-subdomain.surge.sh
```

The deployment folder contains only the user edition.
