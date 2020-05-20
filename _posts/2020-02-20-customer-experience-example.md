---
layout: page
title: "Customer Relationship Experience: Example Plan"
subtitle: "The inside of my brain during implementation and rollout"
date: 2020-02-20 21:21:21 +0530
categories: ["Technical Account Management"]
---

The following is a scrubbed version of a hypothetical plan I laid out as a test exercise on how to build customer relationships in the initial product adoption phase.

### General Details

**The setup:** Versayce recently signed on for FooBar’s Enterprise performance and availability monitoring platform. They’ve already done a proof of concept to validate FooBar’s product and are ready to start ramping up.

**The goal:** Develop relationships and work with key stakeholders to implement FooBar on their system.

**The Versayce People:** VP of Engineering, Director of Observability and Performance, Sr. DevOps Engineer and a Software Developer

**The FooBar Person:** Me, the Technical Account Manager. Hello!

### Initial Contact and Engagement

My first step after the contract is signed will be to send an email officially welcoming all contacts to the platform and congratulating them on a successful proof of concept. Included in the email will be an agenda for a 30 minute kickoff meeting and some suggested times/days. The remote meeting will be a chance to be face to face with everyone and set expectations about support engagements, availability and review Versayce’s short and long-term goals for monitoring performance and availability.

The meeting itself should only have 15 minutes of material to cover in order to allow for light conversation and scheduling a followup meeting to come up with a training plan with the Primary Champion, Primary and Secondary Users. Assuming the VP of Engineering joins the kickoff, the important bits to highlight will be  company health, the successful POC, projected ROI and how I will be involved in the rollout.

If the account is large enough or has enough growth potential, I would check with my manager to approve an onsite and, instead of a remote call, outline a half-day onsite visit that will encompass both the 30 minute kickoff meeting along with planning the rollout. We will review Versayce engineering initiatives and identify the best ways to leverage FooBar for those projects.

Regarding how I would engage with each contact, I try to consider their day-to-day and how I can fit into it in a meaningful way. What do they care about?

### Persona-specific dynamics

1. **Key Business Contact - VP of Engineering**

The VP of Engineering is in constant meetings and steering the helm of a critical department at Versayce. This person primarily cares about system reliability, uptime, impact on the engineering team, overall ROI, and the long-term health of FooBar as their vendor. (The startup world can be hectic and integrating a product into your system only to have the company fail is a bit of a nightmare scenario.)

The most important note here: Don’t waste the VP’s time! Interactions will be few and far between so they need to be impactful and speak to high level concerns. Unless onsite, I will not schedule more than 15-30 minutes of the VP’s time to check in. This person is most likely approving big sale items and wants to know they’re getting a solid ROI.

2. **Primary Champion - Director of Observability & Performance**

At this point in the process, the Primary Champion is all in. My role here is to keep in contact with them on the rollout and implementation plan, partner with them to remove blockers and keep things moving. They have a vested interest in success here and my role is to be in their corner to ensure a smooth experience.

I’ll get a weekly standing meeting scheduled with this person along with the Primary and Secondary Users. I’ll keep tabs on usage, support tickets, incidences, and collect information on their upcoming projects, provide internal documentation, screenshots, training slide decks, and any relevant code snippets. During QBRs I will invite both the VP of Engineering and the Primary Champion to review wins, usage and FooBar’s product roadmap as it relates to their implementation.

3. **Primary User - Sr. DevOps Engineer**

The Sr. DevOps Engineer will have a keen focus on smooth deployments so I’ll set aside time to review their deployment process, how they handle CI/CD and the process of deploying on-prem satellites for production. We’ll keep online communications via Slack and carve out time for a weekly 15 minute meeting along with ad hoc training for their internal teams.

From there, I’ll compile a shortlist of resources related to using FooBar for deployments and identify upcoming minor deployments that will be good candidates for integrating FooBar. The reason I prefer to focus on the little deployments/projects first is they are low risk and will help users gain confidence and start solidifying habitual FooBar use. I will also keep in mind that a Senior DevOps Engineer may be a bit more resistant to changing their habits and adopting new technology so I’ll endeavor to highlight all the ways FooBar is similar to their previous tools as well as the ways it can make their work life easier.

4. **Secondary User - Software Developer**

The approach for this persona is very similar to the Sr. DevOps Engineer, except the data they want to review will be around actual application performance. Once I know the scope of their development work and primary languages they use, I’ll write up a short email with relevant docs and see if there are any application features that could use performance optimization or any current small projects they want to run performance tests on where we could integrate FooBar in developer mode. From there, the cadence will be the same as the Sr. DevOps Engineer.

For both the Primary and Secondary User, the financial aspects that concern the VP of Engineering and the Director of Observability and Performance are irrelevant to them. They will be getting their hands dirty and are already using a plethora of technologies to build and maintain their own product. They don’t care about funding rounds or current big name clients, they just want FooBar to work and improve their day-to-day instead of being one more obstacle to getting things done. My role here is to help cut down on the cognitive load, unbend the learning curve, and be a reliable problem solver and source of useful FooBar information.
