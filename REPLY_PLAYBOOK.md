# CariGold reply playbook

Use these as structures, not copy-paste spam. The goal is to be useful in the public thread first.

## 1. Someone asks how much an app/system costs
Do not start with a price. Break cost into scope drivers: existing code, user roles, backend, payments, maps/location, notifications, admin, third-party APIs, launch requirements. End with one or two questions that materially change the estimate.

## 2. Someone has a manual business process
Explain a simple system model: users/roles → core records → statuses/workflow → automation → reports. Mention what can stay manual in v1 to reduce scope.

## 3. Someone wants “AI”
Separate AI from normal deterministic logic. Ask what input goes in, what output is expected, what must be reliable, and where a human review step is acceptable.

## 4. Someone wants a marketplace
Mention the two-sided flows separately: buyer, seller, platform/admin. Call out commissions, payouts, order states, disputes/moderation and notifications.

## 5. Someone has an unfinished project
Ask for stack/repo access only after they contact you. Publicly explain that the first step is an audit: current architecture, blockers, deployment, database, integrations, error logs and unfinished scope.

## 6. Someone asks “WordPress or custom?”
Answer based on product logic. WordPress is fine for content/simple commerce; custom becomes useful when workflows, roles, dashboards, automation or integrations are the actual product.

## 7. Someone asks about payment integration
Discuss payment flow, webhooks, idempotency, payment states, refunds/cancellations and reconciliation — not only “connect API”.

## 8. Someone asks about MVP
Recommend the smallest end-to-end workflow that proves value. Avoid building every future role, report and automation in v1.

## What not to do
- Do not reply “I can do it, PM me” in normal discussion sections.
- Do not post generic praise or filler to increase message count.
- Do not claim client cases that are actually demos.
- Do not compete on “cheapest developer”.
- Do not dump a giant stack list unless the thread is specifically technical.
