# Smart Contract Security Reviews

Security audit reports of Solidity smart contracts, written as part of my smart contract security practice.

## Audits

| Date | Project | Report | Key findings |
|------|---------|--------|--------------|
| 2026-05-30 | PasswordStore | [PDF](./2026-05-30-PasswordStore-audit.pdf) | <e.g., access control flaw, on-chain secret exposure> |
| 2026-06-05 | PuppyRaffle | [PDF](./2026-06-05-PuppyRaffle-audit.pdf) | <e.g., reentrancy, DoS via loop, weak randomness> |

## Report structure
Each report includes severity classification, impact analysis, proof of concept, root cause, and recommended mitigation.

## Tools
Solidity, Foundry, Slither, EVM

## Notes
These are audits of educational codebases, done to build practical auditing skills.
