# Security Disclosure Policy

## Reporting Vulnerabilities

To disclose vulnerabilities in any of our websites, email servers, or other non-critical infrastructure, please contact the Blast team via email at [protocol@blastblockchain.com](mailto:protocol@blastblockchain.com). We highly appreciate detailed instructions to confirm the vulnerability.

## Vulnerability Disclosure Process

In the event of discovering a critical security vulnerability, we follow a responsible disclosure process. We reserve the right to silently address and fix the vulnerability without immediately publicly disclosing its existence or nature.

Our disclosure process involves the following steps:

1. **Silent Fixing:** The vulnerability is silently fixed and included in a specific release (X).
2. **Initial Disclosure:** After 4-8 weeks, we disclose that release X contains a security fix.
3. **Public Disclosure:** After an additional 4-8 weeks, we publish detailed information about the vulnerability, giving credit to the reporter with their express permission.

In addition to this policy, we reserve the right to:

- Bypass this policy and disclose details on a shorter timeline.
- Directly notify a subset of downstream users before making a public announcement.

This policy is inspired by the Geth team’s [silent patch policy](https://geth.ethereum.org/docs/vulnerabilities/vulnerabilities#why-silent-patches).

## Defensive Measures during an Incident

While our system does not have fault proofs, allowing us to pause the system in an emergency, we have established criteria for disabling the system during an incident response:

- **Ongoing Attack:** If an attack is ongoing, we will disable or pause to prevent further damage.
- **Suspected Widespread Knowledge:** If we suspect that a vulnerability might be widely known, we will proactively disable or pause.
- **Otherwise:** If there is no ongoing attack or suspicion of widespread knowledge, we will not disable or pause the system.

Our commitment is to prioritize the security and stability of our system and respond to incidents in a responsible and timely manner.