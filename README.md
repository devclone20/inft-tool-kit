# iNFT Tool-Kit

> The hub of every **devclone20** AI agent. Each agent keeps its own repository —
> here they are linked as **git submodules** under [`agents/`](agents). Nothing is
> copied or moved: every folder below is a live pointer to the real repo at a pinned
> commit. Click any `agents/<name>` folder above to jump straight to that agent.

## Why this exists

The org had many scattered repositories and no single place to see the fleet. This
repo is that place — one map of every agent, grouped and navigable, without merging
their histories or breaking their individual iNFT identities.

## Agents

### Public

| Agent | What it is |
|---|---|
| [`agents/iclone`](agents/iclone) | The genesis iNFT agent of the iCLONE line (economy: Virtuals ACP). |
| [`agents/vegeta`](agents/vegeta) | Autonomous crypto trading & market-intelligence agent. |
| [`agents/atlas_corporation_okx_ai`](agents/atlas_corporation_okx_ai) | ATLAS — dual-rail Harness Architect iNFT on OKX (already minted, agent #4460). |
| [`agents/matrix`](agents/matrix) | MATRIX AI Agent — Virtuals Protocol ACP. |
| [`agents/supersayatin`](agents/supersayatin) | SuperSayatin AI Agent — Virtuals Protocol ACP. |
| [`agents/doctorwho`](agents/doctorwho) | DoctorWHO AI Agent — Virtuals Protocol ACP. |
| [`agents/doctor-agent`](agents/doctor-agent) | Doctor — academic / research AI agent (CLI). |
| [`agents/akita-agent`](agents/akita-agent) | Akita — senior-engineer AI agent (CLI). |
| [`agents/forense-ai`](agents/forense-ai) | Forense — forensic / scholar AI agent. |
| [`agents/iIrysframe`](agents/iIrysframe) | iIrys Frame — permanent AI-agent NFT layer vault on Irys × Base. |

### Private (links open only for the owner / collaborators)

| Agent | What it is |
|---|---|
| [`agents/doctor-ai20`](agents/doctor-ai20) | Doctor (legacy, migrated from aigenesis20). |
| [`agents/akitaai20`](agents/akitaai20) | Akita (legacy, migrated from aigenesis20). |
| [`agents/troubleshooting-acp-agentes-virtual`](agents/troubleshooting-acp-agentes-virtual) | Troubleshooting guide for Virtuals ACP agents. |
| [`agents/roadmap.rd`](agents/roadmap.rd) | Roadmap / planning notes. |

## How the links work

These are **git submodules**. On GitHub, each `agents/<name>` is a clickable link to
the real repository. To get all the code locally:

```bash
# fresh clone, with every agent checked out
git clone --recurse-submodules https://github.com/devclone20/inft-tool-kit.git

# or, inside an existing clone
git submodule update --init --recursive
```

Public agents fetch for anyone; private agents require access to those repos.

## The pattern behind every agent

Each agent follows the global iNFT genesis template
**[inft-i01](https://github.com/devclone20/inft-i01)**: a Pi coding agent as the
interactive substrate, the agent's own name on top, its neural soul preserved, and
its economy (where it has one) left untouched. This hub only organizes — it never
changes an agent's identity.
