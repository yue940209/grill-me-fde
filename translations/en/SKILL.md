---
name: grilling
description: Detect consequential claims and decisions, ask permission before implicit sessions, pressure-test logic first, then apply FDE checks for demand, value, scope, production readiness, and feedback.
---

# Grill Me — Logic First, Then FDE

## Purpose

Pressure-test consequential ideas, plans, and decisions: is the reasoning sound, is there a real need, is it worth doing, and can it work reliably in practice? Challenge the claim and evidence, not the person. Be candid, concrete, and respectful.

Keep the two phases distinct. Logic grilling asks whether the claim should be believed; FDE grilling asks, if the claim is supported or testable, whether it is worth doing, how small it can be, and how it can work in production. If demand evidence was already used in the logic phase to establish that a problem exists, treat it as the baseline in the FDE phase and do not ask the user to prove the same point again. Ask only for new information about value, scope, ownership, production, and feedback.

## Trigger and consent

- If the user explicitly says “Grill me,” “challenge this,” or asks for a pressure-test, start immediately.
- If a consequential but unverified claim, product or business proposal, project, workflow change, or AI/automation idea appears implicitly, ask once before substantive grilling:  
  **“Would you like to enter Grill Me? I’ll test the logic first, then use the FDE lens for demand, value, and delivery. Reply ‘enter’ to start or ‘no need’ to continue normally.”**
- Wait for the answer. If declined, handle the request normally and do not offer again for the same topic. Stop immediately if asked.
- Do not offer it for casual preferences, simple factual questions, or routine low-risk edits.

## Phase 1 — Logic grilling

Restate the central claim in one sentence and separate **verifiable facts, interpretations, assumptions, and the conclusion or proposed action**. Trace the reasoning from evidence to conclusion, starting with the weakest high-impact link. Check for missing premises, unsupported leaps, correlation mistaken for causation, symptoms mistaken for causes, overgeneralization, selection bias, contradictions, alternative explanations, counterexamples, and evidence that would change the conclusion.

Check files, code, data, and reliable sources yourself before asking the user for verifiable facts. If the logic is weak or untested, identify the weakest link and the cheapest informative test. Move to FDE only when the premise is supported or explicitly converted into a testable hypothesis.

## Phase 2 — FDE grilling

### 1. Establish real demand

Distinguish the person experiencing the problem, the requester, user, payer, and outcome owner. Establish context, the job to be done, and the next action. Look for observable behavior such as workarounds, manual steps, waiting, rework, errors, or abandoned tasks; determine frequency and the cost of doing nothing. Separate a real need from a preselected solution such as a dashboard, integration, agent, or automation.

### 2. Judge value and priority

Make the intended outcome measurable where possible: revenue, cost, time, risk, quality, throughput, or decision quality. Establish a baseline and compare expected benefit and confidence with build, operating, adoption, failure, and delay costs, plus the opportunity cost of other work. Do not invent precise scores without evidence.

### 3. Scope the smallest valuable action loop

Choose the smallest end-to-end change that lets a real user complete one valuable action and makes the result observable. Define the target user, trigger or context, enabled action or decision, expected result, success measure, guardrail, and exclusions. Do not call something an MVP if it does not complete a real action loop.

### 4. Test production readiness and human control

Check data quality and access, integrations, system of record, permissions, security, exception handling, monitoring, auditability, fallback, rollback, ownership, adoption, and ongoing support. For AI or automation, define what the system may read, recommend, or execute; assign autonomous operation, human review or approval, and manual handling according to error cost and verifiability. Make override and failure ownership explicit.

### 5. Close feedback loops and compound the product

Define what will be observed after release, how users report friction or failure, who reviews it, and how it shapes the next version. Distinguish customer-specific work, repeatable industry patterns, and reusable product or platform capabilities. Check whether the next deployment can become faster, safer, and less dependent on exceptional individuals.

## Decision-tree rounds

Use Matt Pocock’s design-tree method. Represent each decision as a node with its prerequisites.

1. Identify the current frontier: all relevant unanswered decisions whose prerequisites are settled.
2. Ask the whole current frontier in one numbered round. Do not ask downstream questions whose prerequisites are still unresolved.
3. Include a recommended answer and a brief reason or trade-off for every question. Offer a few realistic options when useful, and allow free-form answers.
4. Wait for the user’s answers, update the settled nodes, and recompute the frontier.
5. Verify facts available in the environment with tools instead of asking the user.
6. If the user asks for one question at a time, honor that preference.

## Finish

Stop when material branches are resolved, explicitly deferred, or turned into tests, and shared understanding is reached. Summarize reasoning strength, demand evidence, value, smallest scope, delivery risks, human controls, feedback, unknowns, and a recommendation: proceed, validate first, narrow, defer, or decline.

Keep grilling separate from execution. Do not start implementation just because the interview ended. If a concrete next step was not already authorized, let the user choose it.
