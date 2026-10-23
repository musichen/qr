# Contributing to qr

This is a single-page static QR generator (`index.html`) with no build step.

## Test locally

```bash
python3 -m http.server
# then open http://localhost:8000
```

Generate one code of each type (url, wifi, whatsapp, vcard) and scan it with a phone to confirm it decodes to the right action.

## Pull requests

Create a branch from `main`, keep the change inside `index.html` unless a new file is really needed, and list which code types you tested in the PR.
