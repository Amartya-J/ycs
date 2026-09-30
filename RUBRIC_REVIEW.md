# ReadyRoute rubric self-review

This is a strict self-assessment against the supplied Young Coders' Sphere rubric, not an official score. Scores use the rubric's listed levels rather than invented points between levels.

## Before and after the revision

- **Creativity (25 points): 16 → 16.** The combination of a household plan, a transparent response queue, specialist-aware capacity reservations, and manual device relay is useful. The core approach still resembles existing emergency intake systems, so the top originality tier is not justified.
- **Complexity (15 points): 10 → 15.** The working app now combines explainable time-sensitive scoring, a deterministic queue-wide capacity planner that avoids double-booked suggestions and preserves specialist capability, plus an encoded manual relay with schema validation, duplicate handling, and an accidental-change checksum. That is a substantial set of interacting algorithms for a single-file prototype. This is not a secure or validated dispatch system.
- **Potential impact (20 points): 14 → 14.** It addresses the emergency prompt and could contribute to SDG 11 and SDG 13. No field trial demonstrates improved outcomes, and the prototype cannot operate globally or during a real incident.
- **Feasibility (10 points): 7 → 7.** The offline single-file demonstration runs without a server. A real deployment still requires emergency-management partners, privacy controls, reliable synchronization, operations, and testing.
- **User interface (20 points): 7 → 14.** The revision adds an illustrated three-step journey, distinct type styles for headlines, controls, and data, a broader color palette, responsive layouts, readable form fields, visible scoring reasons, a resource inventory, keyboard focus styles, larger text, and a partial Spanish interface. The relay controls include explicit privacy and transfer guidance. It has not been tested with users or assistive technology, so I would not claim 20.
- **Presentation (10 points): 4 → 7.** The current video is a 129-second narrated MP4 with synchronized open captions. It demonstrates fictional inputs, ranking, resource matching, relay, and assignment through a designed scenario. It does not contain a live screen recording of the HTML interface, so I would not claim the top tier.

**Total: 58 → 73 out of 100.** This is an evidence-based estimate, not a competition result.

## Fixes made after scoring

1. Rebuilt the app's visual hierarchy around a project-specific illustration and consistent color, typography, spacing, and mobile layouts.
2. Added capacity-aware resource matching that checks need category and any mobility, language, or power requirement. A coordinator must confirm assignment, which reduces simulated capacity.
3. Rebuilt the slides and video with matching visuals, a worked household scenario, an explained queue, a resource suggestion, and pilot measures.
4. Replaced the silent video with an MP4 containing spoken narration and synchronized captions. The video is under the rules' three-minute limit.
5. Added a manual request relay code with input validation, duplicate detection, and a typo checksum. It contains no free-text details and clearly warns about the remaining location privacy risk.
6. Changed matching from independent first-fit suggestions to a ranked queue-wide reservation pass. General medical capacity is used before specialist backup-power capacity when both fit.
7. Added colored vector graphics to the app and slides. The deck now uses a connected workflow and segmented priority bars, and the video uses the same revised slides. This improves clarity without changing the unvalidated nature of the scoring model.

## What remains to earn higher rubric levels

- Test the UI with people with disabilities, multilingual users, and emergency-response teams. Complete and review every translation.
- Run a controlled pilot measuring intake time, successful resource matches, missed needs, and accessible completion rates against an existing process.
- Add secure identity and consent, encrypted synchronization, official alert sources, audit logs, and operational procedures before any real use. The relay checksum provides no security against deliberate changes.
- Record a live UI demonstration if the competition requires visible interaction with the working HTML app rather than a scenario walkthrough.

The priority and matching formulas are educational examples, not validated emergency triage or dispatch rules.
