# Continuity — Defensive Technical Disclosure

This repository hosts the defensive technical publication for **Continuity**, a memory-augmented AI assistant control plane.

## Purpose

This is a **defensive publication**, not a patent assertion. The author places specific technical methods, parameter values, threshold calibrations, and feature combinations into the public prior-art record so that no party may obtain a patent on the same combinations and assert it against the author or third parties practicing the disclosed methods.

The disclosure covers **methods and architectures**, not source code. The underlying Continuity source code remains proprietary under separate license.

## Document

- [**Continuity Defensive Publication v2.0** (May 17, 2026)](./Continuity_Defensive_Publication_v2.md)

## Scope of disclosure

Five methods, combined and publicly released as a Visual Studio Code extension on October 31, 2025:

- **Method A** — Bounded retrieval architecture with code-enforced per-call cap independent of total stored knowledge
- **Method B** — Runtime governance interception of AI agent tool calls (INTERCEPT → PAUSE → EVALUATE → ENFORCE), mapped to OWASP LLM Top 10 (2025) categories
- **Method C** — Defense-in-depth credential scrubbing at five enforcement boundaries with twenty-seven provider-specific patterns and a Shannon-entropy fallback
- **Method D** — Multi-signal automatic relationship inference between architectural decisions plus Markov chain prediction of next-decision tag sets
- **Method E** — Named "Memory Amplifier" threat model extension specific to memory-augmented AI assistants

## Acknowledgment of prior art

The document explicitly acknowledges related published or commercial prior art (Mem0, MemGPT/Letta, OpenAI Assistants `file_search`, Azure AI Search, NeMo Guardrails, AWS Bedrock Guardrails, Invariant Labs Guardrails, IsolateGPT/SecGPT, Yelp `detect-secrets`, TruffleHog, GitGuardian, LLM Guard, OWASP MCP01:2025, OWASP ASI06:2025, ADR-tools, MADR, Log4brains, Kantara, Hindle et al. 2012, and others) and does NOT claim invention of the underlying generic methods. The disclosure is of specific combinations, parameter choices, and named threat models.

## Citation

Goncalves, T. (2026). *Continuity: Persistent Decision-Centric AI Cognition with Runtime Governance, Bounded Retrieval, and Defense-in-Depth Credential Scrubbing — Defensive Technical Disclosure v2.0.* GitHub. https://github.com/Thiagoscode/continuity-defensive-publication

## Timestamp anchor

Initial commit and annotated tag `defensive-pub-v2.0-2026-05-17` establish the publication date.

## Related

- [Thiagoscode/continuity](https://github.com/Thiagoscode/continuity) — public mirror of the Continuity codebase

## Author

Thiago Goncalves — Hackerware LLC.

## License

Document content: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Source code referenced in this document remains under separate proprietary license held by the author.
