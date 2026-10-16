# Public Prototype v0.1 — Scope and Release Plan
**Founder:** Rie Nakahara · **Updated:** 2026-10-16 · **Target:** 2026-12-31  
**Status:** Proposed scope following Product Vision Update #002; no application has been built by this document.

## Core outcome
Demonstrate one Japanese-language information journey that is welcoming and useful: choose a shopping intention, examine researched local options, understand return-trip questions and uncertainty, and leave with an actionable confirmation checklist. A completed information journey does not mean a booked ride or guaranteed safe trip.

Older adults remain the research/accessibility priority. Joyful wording is founder intent, not evidence that everyone wants a cheerful persona or memories.

## Simplest proposed flow
1. **Welcome:** 「今日はどんなお買い物を楽しみたいですか？」 with a clearly visible 「買い物の方法をすぐ確認する」.
2. **Optional inspiration:** choose a food/meal idea or skip. Any story/recipe example is clearly fictional; recipe content must be reviewed for factual accuracy, with no medical dietary advice.
3. **Practical intention:** store visit / another way to obtain groceries / finding an appropriate human contact. Show these as options, not a ranked judgment.
4. **Local options:** a small reviewed set for one area; show conditions, date checked, official source, and unknowns. Keep selection voluntary. No exact home, health, income, account, or eligibility determination.
5. **Complete the plan:** highlight return transport, bags, boarding, cost, and what the person must confirm. Provide plain text/print, back, restart, and exit.

This is a proposed flow to compare with practical-first alternatives. It is not final UI or a validated journey. Never imply that 「相談」 connects to a staffed Lab service. Real contact roles and availability require source checks.

## Scope tiers
| Tier | Include / decision |
| --- | --- |
| Must have | Japanese interface; readable text; simple respectful choices; optional welcome/inspiration; direct access to practical help; one locality and scenario; traceable facts and unknowns; printable summary; no login; documented limits. |
| Optional after core passes | One openly fictional character with a few scripted exchanges and a no-character route; one fictional recipe/story card. Label a scripted demo accurately, not as live AI. |
| Deferred | Open-ended generative AI, user memory entry/uploads, persistent memory, real-person representations, deceased-person recreation, voice cloning, live family invitations, matching/booking, scent/taste hardware, cognitive screening, emotional profiling, medical functions, payments/credits. |

Default: fictional demonstration content only. If user-entered personal material is later requested, revisit data handling and consent first. Do not make “nothing is stored” promises without checking browser storage, hosting logs, and any external transmissions.

Drop the character before cutting factual reliability, accessibility, or the practical journey. Do not implement every welcome-screen concept or require a companionship choice. The Japanese name 「コンパニオン」 is excluded; the final name remains open.

## Content and accessibility gates
One manageable locality remains to be confirmed through Mission #002. Koshigaya is a prior planning candidate, not a verified service recommendation. No local services were newly audited for this vision update.

Each published real option needs provider/role, official link, coverage, applicable conditions, source date, last checked date, and explicit unknowns. Distinguish fare support from a ride service. Historical examples do not guarantee current operation. A named reviewer must maintain the limited dataset; otherwise mark outdated claims pending confirmation.

Use the [existing ethics principles](../ethics-privacy/principles.md). Assess keyboard operation, screen readers where available, visible focus, contrast, zoom/reflow, large controls, plain Japanese, voice-independent operation, and printing. Do not claim universal accessibility or WCAG conformance from automated checks alone. No interaction while crossing roads, boarding, or driving should be necessary; the proposed demo is for planning at a suitable stopping point.

## Schedule and decision gates
| Period | Gate / review output |
| --- | --- |
| Oct 19–31 | Mission #002 support comparison, fictional scenario, candidate information gap, and optional-joy questions. Record evidence against the app hypothesis too. |
| Nov 1–15 | About 3–5 screens, clickable/paper flow, source schema, skip/virtual-label checks; review before build. |
| Nov 16–30 | Build one responsive end-to-end journey with source-backed data. Keep code in the existing repository and select maintainable hosting during implementation. |
| Dec 1–15 | Functional, content, accessibility, fictional-scenario, and optional-character tests; fix critical defects. Actual older-adult participation only with appropriate consent; disclose if absent. |
| Dec 16–23 | Reverify service facts, links, print route, hosting/privacy behavior, and release candidate. |
| Dec 24–31 | Buffer, public URL verification, limitations/test record, and a separate LinkedIn demonstration drafted for explicit approval. |

The deadline is a target, not a guarantee. Monday 08:00 JST checkpoints remain 30–60-minute research/review/decision sessions; do not duplicate the reminder. Larger research/build/test sessions require explicit requests and protected time. No background execution is implied.

## Release acceptance
- One complete practical scenario and a direct skip past optional inspiration.
- No invented services, availability, memories, clinical effects, or booking success.
- Users can distinguish fictional/scripted content from real-service information.
- Critical navigation, accessibility, and content defects resolved; untested cases disclosed.
- Public URL, source code, provenance, test evidence, and limitations published.
- No sensitive-data collection or unauthorized sharing; no essential help conditional on participation.
- No dementia-prevention, memory-improvement, or therapeutic claim.
- If only an interface demo can be supported, label it accurately and identify unmet original criteria.

## Outstanding decisions
Which locality and exact information need? Do users prefer a practical-first entry? Is a fictional character wanted and worth maintaining? Which terms feel natural? How will offline/supporter access actually work? Who reviews changing service information? No decision here establishes user demand.

See [founder vision](product-vision-002.md) and [research backlog](../research/joy-companionship-memory-backlog-002.md). Preserve Mission #001 and keep ClearJP separate.
