# Skycoin Reference Implementation — Product Status

Canonical SKYCOIN4444 branch **#55**.

This repository already contains a substantial TypeScript/React application and Express/tRPC server surface. The goal of this checkpoint is verification and truthful product boundaries, not adding decorative scaffolding or claiming that optional integrations are live.

## Exact-head merge gates

- `pnpm install --frozen-lockfile`
- `pnpm check`
- `pnpm test`
- `pnpm build`
- `pnpm audit --prod --audit-level high`

## Boundaries

Source code, configuration, or dependencies alone do not prove a production integration. This checkpoint does not claim a reachable production database, applied production migrations, live OAuth, wallets/chains, payments, AI providers, object storage, email, production secrets, TLS, monitoring, backups, restore drills, HA, compliance certification, or a production deployment unless separate runtime evidence verifies them.

Mock/test data is never described as live-provider evidence. Features whose required provider configuration is absent must remain unavailable or fail clearly.

**Status: engineering beta / reference-implementation stabilization checkpoint.**