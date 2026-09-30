# ReadyRoute rubric self-review

This is a strict self-assessment against the supplied Young Coders' Sphere rubric, not an official score. Scores use the rubric's listed levels rather than invented points between levels.

## Before and after the revision

- **Creativity (25 points): 16 → 16.** The household-plan and response-queue combination is useful, and capacity-aware matching adds a distinct feature. The core approach still resembles existing emergency intake systems, so the top originality tier is not justified.
- **Complexity (15 points): 10 → 10.** The app includes transparent scoring, wait-time calculation, access-needs matching, capacity updates, local persistence, export, and translation support. It lacks secure synchronization, official data integration, and validated routing or optimization, so I would not claim the top tier.
- **Potential impact (20 points): 14 → 14.** It addresses the emergency prompt and could contribute to SDG 11 and SDG 13. No field trial demonstrates improved outcomes, and the prototype cannot operate globally or during a real incident.
- **Feasibility (10 points): 7 → 7.** The offline single-file demonstration runs without a server. A real deployment still requires emergency-management partners, privacy controls, reliable synchronization, operations, and testing.
- **User interface (20 points): 7 → 14.** The revision adds an editorial visual system, stronger typography, responsive layouts, readable form fields, visible scoring reasons, a resource inventory, keyboard focus styles, larger text, and a partial Spanish interface. It has not been tested with users or assistive technology, so I would not claim 20.
- **Presentation (10 points): 4 → 7.** The revision replaces the silent AVI walkthrough with a 118-second narrated MP4 and synchronized open captions. It demonstrates fictional inputs, ranking, resource matching, and assignment. It does not contain a live screen recording of the HTML interface, so I would not claim the top tier.

**Total: 58 → 68 out of 100.**

## Fixes made after scoring

1. Rebuilt the app's visual hierarchy around a project-specific illustration and consistent color, typography, spacing, and mobile layouts.
2. Added capacity-aware resource matching that checks need category and any mobility, language, or power requirement. A coordinator must confirm assignment, which reduces simulated capacity.
3. Rebuilt the slides and video with matching visuals, a worked household scenario, an explained queue, a resource suggestion, and pilot measures.
4. Replaced the silent video with an MP4 containing spoken narration and synchronized captions. The video is under the rules' three-minute limit.

## What remains to earn higher rubric levels

- Test the UI with people with disabilities, multilingual users, and emergency-response teams. Complete and review every translation.
- Run a controlled pilot measuring intake time, successful resource matches, missed needs, and accessible completion rates against an existing process.
- Add secure identity and consent, encrypted synchronization, official alert sources, audit logs, and operational procedures before any real use.
- Record a live UI demonstration if the competition requires visible interaction with the working HTML app rather than a scenario walkthrough.

The priority and matching formulas are educational examples, not validated emergency triage or dispatch rules.
