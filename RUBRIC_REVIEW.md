# ReadyRoute review — 30 September 2026

This is a provisional self-assessment of the educational prototype, using only the score bands in the [YCS rubric](https://www.youngcoderssphere.org/_files/ugd/915247_436160c43c8c41558af44de9015c4585.pdf). It is not a competition score or a claim of eligibility.

| Category | Score | Reason |
| --- | ---: | --- |
| Creativity | 15/25 | The combination of household planning, transparent queueing, resource reservations, and manual relay has some creative aspects, but resembles existing intake systems. |
| Complexity | 15/15 | Scoring, capacity-aware matching across a ranked queue, and encoded relay with validation are interacting algorithms. |
| Potential impact | 10/20 | The concept addresses the emergency prompt, but this offline simulation has no demonstrated real-world effect. |
| Feasibility | 4/10 | A real deployment would need secure synchronization, trusted data, trained responders, governance, and field validation. |
| UI | 15/20 | The page has labeled inputs, visible priority reasons, responsive styles, and basic accessibility features. No user or assistive-technology testing supports the top band. |
| Presentation | 7/10 | The 129-second captioned video explains the concept and a scenario, but uses slides rather than a live app demonstration. |
| **Provisional total** | **66/100** | Subject to hands-on browser and user testing. |

## Checks completed

- The HTML's inline JavaScript passes `node --check`; the document parses without duplicate IDs or broken in-page anchors.
- Scoring, general-resource preference, queue-wide capacity reservation, relay round trip, and relay corruption rejection pass focused function checks.
- The MP4 container reports 129 seconds, below the three-minute limit. The caption file ends at 2:09.
- The ZIP passes its integrity check. The app source and packaged app HTML are byte-identical.
- Browser storage failures now produce an error message when saving a request or importing a relay code, rather than claiming success.

## Remaining limitations

- A live browser walkthrough and assistive-technology test were unavailable in this environment. The video does not show live interaction with the app.
- The score is illustrative and unvalidated; no real responder should use it to triage requests.
- The relay code is neither encrypted nor authenticated. It contains a location and access needs.
- No public video or code URL, team member list, or parental consent response has been verified for the submission form.

## Eligibility blocker

The [YCS rules](https://www.youngcoderssphere.org/_files/ugd/915247_a3f592320cc34f9a88c830c931057a17.pdf) prohibit AI-generated material. ReadyRoute was produced with AI assistance and must not be represented as an eligible team-authored submission. This review is for technical feedback; the team would need its own independently authored work and should verify the applicable round with the organizers before submitting.
