## Longer Reflection Version

This weekend, I had one of those moments where **agentic coding** stopped feeling like an interesting experiment and started feeling like something that can genuinely change how I think about **software delivery**.

I have been playing around with agentic coding since early 2025, primarily with **Cursor** at first. Over time, I have tried it across different kinds of work: greenfield personal side projects, brownfield codebases, bug fixes, documentation, PR reviews, review fixes, re-reviews, and even infrastructure/deployment problem-solving.

That last part has been especially interesting to me.

Some of my most memorable experiments were not just about writing application code. I have seen agents help reason through **Caddy reverse proxy configuration** on an AWS Lightsail instance, connect to a server over SSH, inspect the environment, and help think through a deployment plan.

That is when agentic coding starts to feel closer to **agentic engineering**.

Not just “write this function.”

More like:

**Understand the system.
Reason through the constraints.
Make a plan.
Execute carefully.
Review the result.**

This weekend, that shift became even more real for me.

I was out shopping with family, while my laptop was plugged in and running at home. In the past, that would have meant the work had to wait. But this time, I was able to remotely nudge my coding agent forward, review progress, give direction, and keep the work moving.

That experience stayed with me.

Not because I was trying to work every minute of the weekend. Actually, the opposite. I wanted to honor family time, but I also had a few personal side projects where momentum mattered. The ability to keep development moving in small, controlled steps while I was away from my desk felt like a meaningful shift.

Over the last few weeks, I have been experimenting with **Claude, Codex, and Cursor** in different roles.

In one workflow, **Claude was the implementor**, while **Codex and Cursor acted as reviewers**. In another workflow, **Codex implemented and Cursor reviewed**. I have been alternating between tools and models for implementation, PR reviews, review fixes, and re-reviews.

The biggest learning for me so far is this:

**The power is not just in one model.
The power is not just in one IDE.
The power is in the workflow.**

Agentic coding works best when the engineering process around it is strong.

I front-loaded the work with as much clarity as possible: **specs, PRDs, vertically slices detailed GitHub issues, test-driven development, review expectations, and clear instructions** for how the agent should interact with the repo and PRs.

That part matters a lot.

Without guardrails, AI can move fast in the wrong direction. With **guardrails, specs, tests, and review loops**, it has a much better chance of producing code that follows the intent of the system.

I also found that **multiple reviews across different tools or models can improve confidence**. One agent implements. Another reviews. A third can re-review or validate the fixes.

It is not perfect, and it does not remove the need for human judgment, but it creates a better feedback loop.

**The human is still responsible for direction, architecture, validation, and quality.**

**The agent provides leverage.**

What I love most so far is the ability to code from almost anywhere, as long as my machine is available and the workflow is set up properly. New features, bug fixes, documentation, PR reviews, PR review fixes, and re-reviews can all keep moving without me being physically in front of my laptop.

What I dislike most is the constant permission prompts. Too many manual interventions break the flow, especially when the whole point is to let the agent continue working within a trusted and well-defined boundary. That part of the experience still needs to improve.

But even with that friction, I can already see the direction this is going.

This is not **“AI replacing developers.”**

At least that is not how I see it.

To me, this is **hands-on engineering leadership evolving**.

It pushes us to get better at writing specs.
Better at slicing work.
Better at defining acceptance criteria.
Better at test-driven development.
Better at code review.
Better at creating guardrails.
Better at designing systems that are understandable not just to humans, but also to agents working alongside humans.

And it also pushes us to think beyond code generation — into debugging, deployment, infrastructure, operations, and the broader discipline of **agentic engineering**.

**Agentic coding has already changed how I think about software delivery.**

I am still early in this journey. I am still experimenting. I am still learning where it works well and where it needs supervision. But I am convinced this is worth serious exploration by engineering teams.

Curious how others are using agentic coding workflows.

#AgenticCoding #AgenticEngineering #SoftwareEngineering #AI #EngineeringLeadership
