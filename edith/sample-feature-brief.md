# Sample Feature Brief (Fictional)

*This is a fictional sample feature brief created to test Edith’s workflow. It contains intentional issues for verification purposes.*

## Summary and Problem
We want to build a "super fast" notification system that alerts users instantly when they receive a message. The system should be easy to use and work across all devices.

## Target Users and Context
- Users: Anyone with a smartphone or computer.
- Context: Real-time messaging apps.

## Evidence and Current Alternatives
- Evidence: Users complain about slow notifications in existing apps (based on anecdotal comments on social media).
- Current alternatives: Push notifications via Firebase, APNs, and web push; polling-based approaches.

## Goals and Success Measures
- Goal: Deliver notifications within 1 second of message send.
- Success measure: 95% of notifications delivered within 1 second.
- Additional goal: Be "easy" for developers to integrate (no specific metric).

## Non‑Goals
- Not concerned with battery consumption.
- Not concerned with supporting legacy devices older than 5 years.

## Proposed Approach and Alternatives
- Approach: Use a persistent WebSocket connection to a central server that pushes messages instantly.
- Alternative: Use SMS gateway for guaranteed delivery (more expensive).

## MVP Boundaries
- Included: WebSocket server, client SDK for iOS/Android/Web, basic UI to show notifications.
- Deferred: Message history, rich media attachments, group chat functionality.

## Assumptions and Open Questions
- Assumption: Users have a stable internet connection 99% of the time (no evidence provided).
- Open question: What is the exact latency threshold users perceive as "instant"?

## Risks and Next Decisions
- Risk: Server overload if many users maintain persistent connections.
- Next decision: Choose between horizontal scaling of WebSocket servers or switching to a hybrid push/pull model.

---
*Note: This brief intentionally includes:*
- *One material missing requirement: No requirement about security or privacy of message content.*
- *One ambiguous statement: “Be 'easy' for developers to integrate” (no observable criteria).*
- *One contradiction: Claims “Users complain about slow notifications” (based on anecdotal social media) while also stating no formal user research was conducted.*
- *One unsupported technical assumption: “Users have a stable internet connection 99% of the time” (no data cited).*