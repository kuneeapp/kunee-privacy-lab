# Local test guide

This is a conceptual checklist for a disposable browser-lab session on an ephemeral local chain. It does not contain deployable code or instructions for connecting to a public chain.

## Before starting

- Use only the project's intended local lab interface and its documented local-chain tooling.
- Confirm the selected network is the ephemeral local chain with chain ID `31337` and a local-only RPC endpoint.
- Do not connect a wallet containing real funds, import an existing account, or use a public RPC endpoint.
- Use only throwaway local test accounts and valueless local test assets.

## Conceptual walkthrough

1. Start a fresh local lab session using the project's established local workflow.
2. Check the network indicator in the lab and confirm chain ID `31337` before taking any action.
3. Use the lab's local-only setup to create fresh disposable test state.
4. Exercise the lab's intended sample flow with local test accounts and valueless test assets; observe the expected state changes and any displayed errors.
5. Reset or stop the local session when finished. Treat its chain state and test accounts as disposable.

If the interface shows a public network, a non-`31337` chain ID, an unfamiliar account, or a public transaction prompt, stop without approving it and report the issue to [support@kunee.app](mailto:support@kunee.app).

## Limits

This walkthrough is not evidence of production behavior, public-chain compatibility, privacy between real users, or contract safety. The browser lab has no public mainnet access. Never put secrets, wallet private material, recovery phrases, private keys, or real user data into a test session or report.