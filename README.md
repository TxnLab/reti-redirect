# Réti Open Pooling - Production Redirect

This repository contains the redirect configuration for the legacy reti.vercel.app domain.

The `vercel.json` file is configured to permanently redirect all traffic from the old domain to https://reti-fnet.nodely.io/, preserving any path segments in the URL.

For example:

- `reti.vercel.app/` → `https://reti-fnet.nodely.io/`
- `reti.vercel.app/validators/1` → `https://reti-fnet.nodely.io/validators/1`

## GitHub Repository

This repository is a simple redirect setup. The actual repository can be found at https://github.com/algorandfoundation/reti.
