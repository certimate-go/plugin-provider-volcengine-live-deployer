# Certimate Volcano Engine Live deployer

Deploys certificates to Volcano Engine Live domains. Uses the existing
`volcengine` access type.

Build with `make build` and run checks with `make test`. The protected
release workflow takes a `vX.Y.Z-detach` trigger tag matching the manifest
version and publishes platform ZIPs under `build/` at the formal tag.
