---
  layout: clean
  permalink: /draft/
  version: draft
  is_draft: true
  title: 'Open Manifesto for AI Agents Touching Production Systems'
  description: 'Governing the Shift from Automation to Autonomy. A set of guiding principles for AI agents operating in production systems.'
  motto: 'Principles required to trust the machines.'
---
# Open Manifesto
# **for AI Agents**
> _Touching Production Systems_

> Governing the Shift from Automation to Autonomy.
A set of guiding principles for AI agents operating in production systems.

##### We are standing at the edge of the Probabilistic Era.

For the last twenty years, professional automation was built on the foundation of **Determinism**. In Infrastructure, we used Ansible and Terraform. In Finance, we built rigid algorithms. If a system broke, it was a bug in the logic. The liability was static.

##### The Shift

Today, we are handing control to systems that do not follow instructions, they interpret intent.

**AI Agents are not scripts.** They are probabilistic operators. They reason, plan, and execute. While this promises exponential velocity, it introduces a new, existential risk: _Stochastic Liability_.

To build a future where autonomous agents can be trusted with critical systems, we adhere to the following principles:

<!-- PRINCIPLES -->

## 01
### The Principle of Separation
#### Reasoning must be separate from action.
Intent must be decoupled from Execution. An agent must never be granted the authority to 'think and act' in a single, opaque atomic step. Just as Terraform separated Plan from Apply, Agentic workflows must separate Reasoning from Action.

## 02
### The Principle of Provenance
#### Every output must carry its own creation story.
Output without lineage is hearsay. In a probabilistic workflow, the final artifact is meaningless without the context of its creation. We require a cryptographic link between the agent's identity, the input context, the model used, and the final output.

## 03
### The Principle of External Sovereignty
#### No agent can be its own authority.
Safety guardrails must exist outside the agent's cognitive loop. We cannot rely on an LLM to 'promise' that it checked for security. Policy must be deterministic code, enforced by a neutral orchestrator.

## 04
### The Principle of Immutable Evidence
#### Logs must be proofs, not just text.
In the event of a failure, a simple text log is not sufficient. Autonomous systems require a chain of custody that is mathematically indisputable. Every decision and state change must be signed and sealed.

## 05
### The Principle of Ephemeral Identity
#### Static keys are a failure of architecture.
Autonomous agents are transient processes. They should not hold long-lived credentials. Identity must be ephemeral, issued only for the duration of a specific task, and cryptographically bound to the workload.

## 06
### The Principle of Capability Isolation
#### Agent Rule of Two [*](https://ai.meta.com/blog/practical-ai-agent-security/){:rel="nofollow"}
Agents must not simultaneously process untrusted input, access sensitive systems, and perform state-changing operations. If such combinations are unavoidable, external supervision is mandatory.


