---
layout: post
title: Driving Technical Decisions
date: 2018-06-30
---
Most software projects don't need much technical leadership. Most dev teams don't have processes or the skills to drive them. This often results in technical debt, poor tooling, and bad interface designs.

This is unfortunate, because driving technical projects isn't that hard. It's just not something most teams are trained to do. Most projects can be conceived and delivered in three phases: brainstorming, proposal, and spec.

## Brainstorming

Brainstorming is actually the most overhyped of the phases. Certain personalities really thrive on unstructured meetings, and brainstorming provides an excuse. Resist the temptation. If it helps, rename this phase "requirements gathering."

During this phase, aim to elicit and capture two things: possible innovations and stakeholder concerns. People will throw a lot of crap at you. Critically evaluate everything.  Hints:
- Avoid meetings; science shows they don't work
- Prefer asynchronous communications
- Set deadlines for feedback
- Reach out directly to key stakeholders
- Minimize this phase as much as possible; skip it if you can

## Proposal

After brainstorming comes the proposal stage. This is where I start most of my projects. A proposal is like a
specification, but it's like a first draft of the specification.

Do:
- Focus your proposal on interfaces between systems
- Make it concrete, specific, and detailed
- Make it available for review
- Establish an end date for comments

Avoid:
- Meetings where feedback is solicited
- Waiting on everyone to chime in
- Accepting feedback at face value
- Doing more than one review cycle

Maybe have a meeting where you present the proposal. Only do this if your organization's stakeholders are unlikely to
read and respond without one. Meetings present special hazards that are best avoided: bikeshedding, yak shaving, descent
into debate, etc.

## Spec

Once you've written and delivered a proposal, you're ready to turn it into a spec. Spec is like proposal but aims to be
final. Again, resist doing lots of review cycles. Iterating on the plan without feedback from implementation will rarely
help.

Moving from proposal to spec can be straightforward, but often it's not. Your goals have changed from capturing
requirements and proposing a solution, to delivering a roadmap for implementing a solution. The document doesn't change,
but your goal does.

Consider:
- Breaking controversial or large pieces into later development phases
- Capturing insights from review as soft suggestions
- Vetting the spec with key stakeholders

When the spec is prepared, provide it for inspection. This time, do not solicit review. You can still accept feedback,
but the time for feedback has formally passed.

Now you have a spec, and your regular development processes can commence!
