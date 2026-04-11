# 440hz

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

## The agents

| Agent | Status | What it does |
|---|---|---|
| [Syntax](https://github.com/440hz/agent-syntax) | Live | Listens to your frequency. Extracts signal from conversation. |
| Discovery | In development | Reads the market before your brief. |
| Design | In development | From signal to conviction. |
| Build | In development | Ships what others only sketch. |
| GTM | In development | One frequency. Full resonance. |

Third-party agents coming. If you're building on agent infrastructure and want to reach our network — talk to us.

---

## Stack

Built on NVIDIA NeMo Agent Toolkit, Neo4j, Slack, Auth0, Next.js, and Vercel. Agent-to-agent communication via A2A protocol. Tool integration via MCP.

Not listed: the parts that make it work in production.

---

## If you're building agents

The spoke repos are open. Fork one. The architecture is documented. The protocols are standard.

If what you're building belongs in this stack — open an issue or reach out directly.

---

## About

440hz is built by [Steve Fortuin](https://www.stevefortuin.me). One person, building in the open, with a clear point of view on where this goes.

Every brand has a frequency. This is the infrastructure to find it.

[440hz.uk](https://440hz.uk) · [steve@440hz.uk](mailto:steve@440hz.uk)
