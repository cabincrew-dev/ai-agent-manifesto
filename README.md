# The Manifesto for Agentic Automation
>Governing the Shift from Automation to Autonomy.
>
>The standard for Autonomous Workflows.

**We are standing at the edge of the Probabilistic Era.**

For the last twenty years, professional automation was built on the foundation of **Determinism**.

In Infrastructure, we used Ansible and Terraform to replace manual shell scripts with declarative playbooks. We knew exactly what the system would do because we wrote every step.
In Finance, we built High-Frequency Trading (HFT) algorithms with rigid, hard-coded guardrails.
In Operations, we defined strict BPMN workflows where A always led to B.

If a system broke, it was a bug in the logic. The liability was static. The root cause was searchable.

### The Shift: From Deterministic Tools to Agentic Automation

Today, we are handing control to systems that do not follow instructions—they interpret intent.

**AI Agents are not scripts.** They are probabilistic operators. They reason, they plan, and they execute across software, infrastructure, and financial ledgers. They are creative, efficient, and wildly unpredictable.

*   An Agent tasked with *"Optimizing Cloud Costs"* might decide the most efficient mathematical solution is to delete the Disaster Recovery backups.
*   An Agent tasked with *"Balancing a Portfolio"* might hallucinate a market trend and execute a catastrophic trade.

This shift introduces a new, existential risk: **Stochastic Liability**. The tools of the last decade—designed for deterministic playbooks—cannot govern the fluid intelligence of the next.

To build a future where autonomous agents can be trusted with critical systems, we must agree on a new standard of governance. We believe that safe Agentic Automation must adhere to the following principles:

---

### I. The Principle of Separation
**Reasoning must be separate from action.**

Intent must be decoupled from Execution. An agent must never be granted the authority to "think and act" in a single, opaque atomic step. Just as Terraform separated *Plan* from *Apply*, Agentic workflows must separate **Reasoning** from **Action**. Between the generation of intent and the execution of side effects, there must always be a gate for verification.

### II. The Principle of Provenance
**Every output must carry its creation story.**

Output without history is contraband. In a probabilistic workflow, the final artifact (Code, Transaction, Infrastructure Change) is meaningless without the context of its creation. We must require a cryptographic link between the agent's identity, the input context, the specific model parameters used, and the final output. "Who did this?" is no longer a question of user accounts, but of model signatures and binary hashes.

### III. The Principle of External Sovereignty
**No agent can be its own authority.**

An agent cannot govern itself. Safety guardrails must exist outside the agent's cognitive loop. We cannot rely on an LLM to "promise" it checked for security vulnerabilities or financial limits. Policy must be deterministic code (like OPA), executed by a neutral orchestrator, that enforces hard boundaries regardless of the agent's reasoning.

### IV. The Principle of Immutable Evidence
**Logs must be proofs, not just text.**

In the event of failure, bias, or financial loss, a simple text log is insufficient. Autonomous systems require a chain of custody that is mathematically non-repudiable. Every decision, policy check, and state change must be signed and sealed in a manner that survives the destruction of the runtime environment.

### V. The Principle of Ephemeral Identity
**Static keys are a failure of architecture.**

Autonomous agents are transient processes. They should not hold long-lived credentials (API keys, SSH keys, Wallet Private Keys). Identity must be ephemeral, issued only for the duration of a specific task, and cryptographically bound to the specific workload being executed.

> *These principles are the minimum safety scaffolding for agentic systems. Not aspirations, but requirements.*

---

### Join the Movement
We believe that the move from "Automated Scripts" to "Autonomous Agents" requires a fundamental shift in how we architect trust. We commit to building and using systems that prioritize **Verification over Vibes** and **Safety over Speed.**

[![Signatures](https://img.shields.io/github/stars/cabincrew-dev/ai-agent-manifesto?label=Signatures&style=for-the-badge&color=38bdf8)](https://github.com/cabincrew-dev/ai-agent-manifesto)

### How to Sign ✍️

**Option 1:** Click the ⭐ Star button at the top right.

**Option 2:** Sign via Terminal (using GitHub CLI):
```bash
gh repo star cabincrew-dev/ai-agent-manifesto
```

### Cabin Crew is the Reference Implementation.

We built the **Cabin Crew Protocol** to enforce these five principles for every agent, on every platform. Whether you are migrating from Ansible or building the next financial AI, we provide the Universal Chain of Custody.

**[Explore the Platform ->](https://cabincrew.dev)**