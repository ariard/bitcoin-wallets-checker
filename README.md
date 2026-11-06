## Bitcoin Wallet Checker

A toy project leveraging LLM-agents to generate formal proofs based
on a secure abstract bitcoin wallet about a range of bitcoin software
wallets.

This is an experimental project where the idea is to build a knowledge
base on common bitcoin wallet vulnerabilities, ask LLM to refine a
theorem-based abstract bitcoin wallet model and then ask the LLM agent
to go to sweat their asses on deriving the security proofs for them,
while the humans operators can drink romanee conti on the beach.

The search for security proof can be cost-based, i.e after a budget
allocated for a security property, a LLM is not able to demonstrate
that a wallet is secure for a given property, a human operator can
steps in to investigate the failure. Under this approach, the inability
to prove the security property of a software wallet *is* a more
informationally-rich learning to find real-world bugs than a successful
proving.
 
See the `ARCHI.md` for the methological approach relying on Rocq
(we're also considering doing cross-verification with Lean).

The toy project is mostly a teaching experiment for our team to play
with frontier LLMs with real-world software artifac ts, though if we
find interesting findings, we'll disclose them responsibly.

We're used to.
