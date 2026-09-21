---
schemaVersion: treeseed.objective/v1
id: agent-core
projectId: agent
title: "TreeSeed Agent Core Objective"
outcome: "TreeSeed Agent exists to run Treeseed capacity providers, including provider API, provider manager, provider runner, worker runtime, AgentKernel execution, mode scheduling, provider-local capacity enforcement, Docker assets, and runtime tests while preserving its package boundary."
status: active
---

TreeSeed Agent exists to run Treeseed capacity providers, including provider API, provider manager, provider runner, worker runtime, AgentKernel execution, mode scheduling, provider-local capacity enforcement, Docker assets, and runtime tests.

This core objective is the starting direction for the TreeSeed Agent Knowledge Hub. It should influence every package-local workday, research note, implementation proposal, generated artifact, approval request, and release-readiness summary.

Agent owns provider-local runtime execution and must remain assignment-only. It must not become the API control plane, hidden scheduler, web app, admin UI, package workflow owner, or TreeDX product semantics layer.

Agents working in this project should keep outputs grounded in the package README, package-local source evidence, and the TreeSeed package ownership map. When a task would cross into another package's authority, the agent should describe the boundary and route the work to the correct project instead of mutating outside this hub.
