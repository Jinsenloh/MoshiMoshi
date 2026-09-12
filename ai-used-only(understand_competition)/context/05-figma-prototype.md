# Current Figma Prototype

**Link:** https://www.figma.com/design/vAz2Dtc4Xle1BFnbD1YdZM/Assignment?node-id=2005-5

This is the team's live UI prototype for the **Stress & Workload Manager** submission. Treat this file as a snapshot description as of the last time it was reviewed — always check the live Figma link for the current state before making design decisions, since the board may have changed since this was written.

## App concept, as designed so far

A gamified companion app (main character/avatar: **Lily**, level-based with XP) that turns "workload across life domains" into something visual and actionable, with a voice assistant character (**Kiko**) and a social/accountability layer.

## Screens present on the board (left to right, top to bottom)

**Onboarding / home context**
- Phone lock screen & home screen mockups (context frames, likely just for presentation polish, not app screens themselves)
- Character/avatar home screens showing **"Today's Status"** as three live percentages — Mental / Time / Physical — with a growing plant as a visual health indicator next to the avatar

**Status & task balancing**
- **Profile** — avatar (Lily), Level, XP bar, and a "Shop" of redeemable rewards (e.g. Warm Ramen, Zzz Box, Green Cascade, Art Deal, Robe Collection) purchased with in-app points
- **Today's Status (detail)** — overall state label ("Well Balanced" / "Overloaded"), broken down by **Mental, Time, Physical, Social, Errands** as percentage bars
- **Balance My Task** — tasks split into **Must Do / Can Skip / AI Suggests**, each with a point value; a "Balance My Task" action and a "Done" action

**Task management**
- **Task list** (day view, scheduled tasks with times) and **Edit Task**
- **New Task** creation flow with multiple input modes: manual entry, **upload**, **voice**, and **explore/map** — including connecting Google Calendar or Microsoft Outlook to import events
- **Errands Nearby** — a map view showing nearby errands/shopping locations to attach to a task

**Voice assistant & recovery**
- **Voice ("Kiko")** — conversational check-in ("Hey! I'm Kiko. How are you feeling today?"), with a listening state, used to log tasks/feelings by voice instead of typing
- **Recovery** — a menu of recommended recovery actions (Breathing, Power Nap, Quiet Night, Walk Short, Break & Listen), each with a duration and a point reward
- **Breathing exercise** flow — guided timer (e.g. "4-2-4 cycle reset"), in-progress breathing animation screen, and a completion screen ("Well Done!") awarding points

**Community / social**
- **Community** — tabs for "My Group" vs "Public", showing groups (e.g. Study Crew, Workout Group) with member counts and a "Create a Group" action
- **Group leaderboard** (e.g. "Study Crew") — ranks members by points (Sophie, Abu, You, Marcus, Amy) with levels
- **Edit Group** and **Add Friends** (search + friend list with add action)

## How this maps to the brief and rubric

- Directly answers the brief's "shouldn't just track and report" requirement: the app **acts** on load via Balance My Task (rebalancing/pushing lower-priority tasks back) and Recovery (explicit nudges toward rest/breathing/social activity) — this is exactly what Impact (Effectiveness of the Solution) rewards.
- The five-domain breakdown (Mental, Time, Physical, Social, Errands) mirrors the brief's wording almost verbatim — worth calling out explicitly in the submission's Project Overview.
- Gamification (points, levels, shop, leaderboard, groups) is the "novel feature/twist" candidate for the Creativity section — the submission should explicitly name this as the differentiator and explain why it drives adherence (vs. a plain tracker).
- Voice input (Kiko) is a secondary differentiator worth calling out in "What Makes It Different."
- For the Design/Usability score, the current screens show a consistent illustrated, warm/cozy visual style throughout — worth naming as a deliberate visual-consistency choice in the submission.

## Open items / things to double check against the rubric before submitting

- Make sure the ideation trail behind *why* these specific features were chosen (and what was tried and dropped) is documented separately in the ideation board — the Figma prototype alone does not earn Ideation points, only Design/Impact points.
- Recovery/points/leaderboard mechanics should have a one-line rationale ready (why gamification helps this specific problem) since Effectiveness and Differentiation are both scored on reasoning, not just presence of the feature.
