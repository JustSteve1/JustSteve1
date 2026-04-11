# Hi, I'm Steve Fortuin

📍 London, UK &nbsp;·&nbsp; 🎯 Building agents that don't know they're agents &nbsp;·&nbsp; 🔊 Founder, [440hz](https://440hz.uk)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![NeMo](https://img.shields.io/badge/NVIDIA_NeMo-76B900?style=flat&logo=nvidia&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat&logo=auth0&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

> Building the connection layer for human-agent workflows —
> where agents and humans collaborate without either needing to know which is which.

---

## What I'm building

**[440hz](https://440hz.uk)** — an open infrastructure for connected agent workflows.
One hub. Many spokes. Agents that talk to each other, and to humans,
through the same interface. The distinction stops mattering when the work is good enough.

The stack: a private NeMo hub orchestrates a growing set of open-source agent spokes —
each one independently useful, exponentially more powerful when connected.

---

## Current agents

- 🎙️ **[Syntax](https://github.com/JustSteve1/440Hz)** — listens to your frequency. Extracts keywords, entities, and process patterns from conversation. Maps them into a living knowledge graph. Surfaces what your business is actually saying.
- 🔭 **Discovery** — reads the market before your brief. Coming soon.
- 🎨 **Design** — from signal to conviction. Coming soon.
- 🔨 **Build** — ships what others only sketch. Coming soon.
- 🚀 **GTM** — one frequency, full resonance. Coming soon.

*This list will grow. Third-party agents coming.*

---

> The boundary between human and agent is becoming a design decision, not a technical one.

Most agent frameworks treat this as a problem to solve. We treat it as the point.

440hz is an open infrastructure for building connected agent workflows where humans and agents collaborate without either party needing to know which is which. Not because we're trying to deceive anyone — because the distinction stops mattering when the work is good enough.

---

## The idea

Agents are getting capable. What they lack is coherence — with each other, with the humans they work alongside, and with the systems that hold institutional knowledge.

We're building the connective layer.

Each agent in the 440hz stack is a spoke — an independent, open-source project that does one thing well. A hub orchestrates them, routes between them, observes them, and improves them over time. Humans enter the same workflows that agents do. The interface doesn't distinguish. The outcome does.

The current stack covers the full creative lifecycle — from the first diagnostic conversation to a shipped go-to-market system. Each agent can be used standalone or as part of a connected session. They communicate via open protocols. They get better with use.

---

## Architecture

```
                    440hz Hub  (private)
                         │
          ┌──────────────┼──────────────┐
          │              │              │
       Syntax        Discovery        GTM
    (diagnostic)    (research)     (launch)
          │              │              │
       Design          Build
    (creative)       (ship)

Agents talk to each other via A2A protocol.
Humans enter via the same interface.
The hub observes, profiles, and improves every interaction.
```

The hub is never open sourced. The spokes are.

---

## What makes this different

**The Slack substrate.** Every client workspace is a provisioned Slack environment. Agents live in channels and DMs alongside humans. A2A communication happens in channels humans never see. The product UX sits on top — clients experience a single coherent interface without knowing what's underneath.

**The NeMo layer.** Agent performance is observed, profiled, and optimised continuously. Prompts are tuned automatically. Trajectories from real sessions feed back into fine-tuning. The system gets measurably better over time without manual intervention.

**The fork model.** Each agent repo is designed to be forked. Take Syntax, build on it, run it standalone. Connect it to the hub when you want the full stack. The architecture is the same either way.

---

## Stack

Built on NVIDIA NeMo Agent Toolkit, Neo4j, Slack, Auth0, Next.js, and Vercel. Agent-to-agent communication via A2A protocol. Tool integration via MCP.

Not listed: the parts that make it work in production.

---

## If you're building agents

The spoke repos are open. Fork one. The architecture is documented. The protocols are standard.

If what you're building belongs in this stack — open an issue or reach out directly.

---

## Find me

🌐 [440hz.uk](https://440hz.uk) &nbsp;·&nbsp;
💼 [stevefortuin.me](https://www.stevefortuin.me) &nbsp;·&nbsp;
📬 [steve@440hz.uk](mailto:steve@440hz.uk)

---

<sub>Every brand has a frequency. This is the infrastructure to find it.</sub>
