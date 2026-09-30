# ReadyRoute

ReadyRoute is an **offline educational prototype** for the prompt: “How can we use technology to make emergency preparedness and response faster, more accurate, and more equitable for everyone?”

## Open the prototype

Open [index.html](index.html) in a modern browser. No build step, account, or server is needed. All examples are fictional. Nothing is transmitted to emergency services.

## Download the complete project

From the [GitHub repository](https://github.com/Amartya-J/ycs), select **Code → Download ZIP**. Unzip it, then open `index.html` to run the prototype. The presentation, captioned video, captions, transcript, and ready-to-share ZIP are at the repository root.

For a single file, open it on GitHub and select **Download raw file**. To clone the project, run `git clone https://github.com/Amartya-J/ycs.git`.

## What works

1. **My plan:** save a household contact, meeting place, backup route, and access needs in local browser storage; print the plan or delete it.
2. **Request help:** enter a location, need category, urgency, and access barriers. The request is added to the local simulation.
3. **Response view:** see requests sorted by a transparent priority score; review suggestions that reserve simulated capacity in queue order and use general teams before scarce specialists; assign manually, reset, or export JSON.
4. **Manual relay:** generate a compact code for an open request and paste it into ReadyRoute on another device. This is a person-to-person handoff, with duplicate detection and a checksum for accidental changes. It never syncs or sends automatically.
5. **Access:** responsive layout, keyboard-focus styles, semantic form labels, larger-text toggle, and a partial Spanish interface.

## Priority formula

`urgency (10, 20, or 30) + essential need (10 for medical or shelter) + access barriers (6 each, capped at 12) + wait (2 per elapsed hour, capped at 10)`

The formula is **illustrative and unvalidated**. It does not use race, income, or ZIP code. It never dispatches help; a trained person would make decisions. Its factors are shown beside each request so a coordinator can question the ordering.

The resource planner requires the same need category and any selected mobility, language, or power support. It reserves suggestions across the ranked queue so one resource slot is not promised twice, and chooses a general resource ahead of a specialist when both meet the same request. A coordinator must select the assignment; there is no automatic dispatch.

## Privacy and safety boundaries

- Data is stored in the current browser only. It can be viewed by others who use the same device.
- The relay code omits free-text details, but contains location and access needs. It is not encrypted or authenticated. Only share it with someone trusted; its checksum detects typos, not tampering.
- There are no live hazard feeds, official alerts, location services, or emergency dispatch connections.
- Do not use the prototype for real emergencies. Call local emergency services and follow official instructions.
- A pilot would need security, consent, encrypted synchronization, real multilingual review, accessibility testing, and emergency-management partners.

## Presentation and video

- `ReadyRoute_presentation.pptx`: six editable slides, with speaker notes.
- `ReadyRoute_video.mp4`: narrated, captioned video under three minutes.
- `ReadyRoute_captions.srt`: matching caption file.
- `ReadyRoute_transcript.txt`: full narration transcript.

## Source basis

- [Ready.gov](https://www.ready.gov/) on household planning and alerts.
- [FEMA guide to community engagement](https://www.fema.gov/sites/default/files/documents/fema_guide-community-engagement.pdf) on accessible, inclusive communication.

## Competition check

The supplied YCS rules PDF says the video must be shorter than three minutes and the project must have a UI. It also states “no ... use of AI-generated material” under rule 7. The linked [high-school competition page](https://www.youngcoderssphere.org/high-school-competitions) currently displays an agriculture prompt rather than the emergency prompt. Verify the relevant competition round and eligibility before submission.
