<!-- Satellite context file — extends the global hub (~/.claude/CLAUDE.md | ~/.pi/agent/AGENTS.md). Host-neutral; project-specific only. Do not duplicate hub standards here. -->

# Adrena Trading Arena

> A Solana trading-arena / protocol project (Anchor program + SDK + app). Hackathon submission.

**Stack:** Solana + Anchor (Rust) · TypeScript SDK + tests · pnpm. See `Anchor.toml`, `programs/`, `sdk/`, `app/`, `tests/`.

## Common Commands

```bash
anchor build          # build programs
anchor test           # integration tests
pnpm test             # TS test script
```

## Structure

`programs/` (Anchor on-chain) · `sdk/` (TS client) · `app/` (frontend) · `tests/` · `scripts/` · `orchestrator/` · `migrations/` · `bounty-analysis.md` · `docs/` · `resources/`.

## Notes

- See `README.md` and `bounty-analysis.md` for the hackathon context and architecture.
- This repo is the implementation-plan host referenced by the Edict delivery platform (`RECTOR-LABS/edict`) — the Adrena arena-implementation-plan doc is the first real Edict tenant.