---
title: "FCAJ x Agentic AI Build Week: Show Up. Build. Pitch. WIN!"
date: 2026-07-25
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
---

# Summary Report: "FCAJ x Agentic AI Build Week: Show Up. Build. Pitch. WIN!"

## Purpose of the Event

> Any builder, any background, any age, any nationality. If you have an idea, you show up, you build, you pitch.

This event celebrates the spirit that helped FCAJ teams outshine more than 300 global builders and claim the ultimate victory at Agentic AI Build Week. It highlights the relentless effort, breakthrough moments, and untold stories behind that journey.

Participants are invited to join the sharing session, hear how the teams turned ideas into glory, and leave with renewed energy to ignite their own passion for building.

## General Information

* **Event name:** FCAJ x Agentic AI Build Week: Show Up. Build. Pitch. WIN!
* **Format:** Hackathon, team competition, technical demo, and product presentation
* **Role:** Participant
* **Main topics:** AI product design, multi-channel chatbot ordering, business strategy analysis, IT architecture automation, public security monitoring, and AML detection

<div style="display:flex; gap:16px; flex-wrap:wrap; align-items:flex-start;">
  <img src="/fcj-workshop-duongtin/images/4-EventParticipated/event5-1.jpg" alt="Event banner or main photo" style="width:48%; max-width:520px; height:auto;" />
  <img src="/fcj-workshop-duongtin/images/4-EventParticipated/event5-2.jpg" alt="Team photo or project screenshot" style="width:48%; max-width:520px; height:auto;" />
</div>

## Speakers / Key Contributors

* **Joseph Marazota** - Amazon technology expert who shared career encouragement and guidance
* **One Team** - Presented the AI multi-channel food ordering chatbot
* **FBT** - Presented the AI business strategy analysis solution
* **Hackathon architecture team** - Presented the AI assistant for IT architecture automation
* **Public security team** - Presented the AI camera-based crowd monitoring solution
* **Six Piller** - Presented the AI anti-money laundering solution

## Key Projects and Learnings

### General Opening and Encouragement from an Amazon Expert

Joseph Marazota shared his career journey and highlighted the major opportunities available to young people in the AI era. He encouraged participants to challenge old ways of doing things and to step up as future technology leaders in the next two to three years.

The session emphasized several important ideas:

* AI is a support tool, while humans still stay in the loop.
* Technology products are being built much faster than before, sometimes moving from months to minutes or even seconds.
* Continuous learning and self-confidence are essential for long-term growth.

This opening set a positive tone for the hackathon and encouraged participants to treat the event as both a competition and a learning opportunity.

### AI Multi-Channel Food Ordering Chatbot

The One Team project focused on building a chatbot-based ordering experience for KFC, with the goal of removing app switching and making the flow easier for customers. The solution worked through widely used platforms such as Zalo and WhatsApp, which made the experience more natural and accessible.

One important real-world lesson came from McDonald's earlier experiment with AI ordering at the drive-through. That case showed how AI can fail when it does not understand conversation context well enough and ends up making ordering mistakes. The team used that example to justify a simpler and more reliable ordering journey inside chat.

The architecture included:

* Multi-channel input with a message normalization module
* AI to extract intent and ordering purpose
* Menu data collected from the KFC website through Tiny Fish web scraping
* Agent memory to remember user order history and improve personalization

The solution also showed strong practical value:

* Infrastructure cost was around 88 USD per month for about 500 orders per day
* Response latency was only around 3 to 4 seconds
* Infrastructure cost dropped by about 60 percent compared with the traditional approach

The demo included a dashboard for tracking chatbot conversation history so staff could monitor and fix issues quickly.

### AI for Business Strategy Analysis

The FBT team built an AI system to collect, summarize, and analyze competitor strategy data to support risk management and business planning. The main challenge was that strategic information and financial reports are often scattered across many sources, which makes manual analysis difficult and time-consuming.

The solution helped combine business signals and assess the impact of a new strategy in terms of both profit and risk. The technical stack used AWS Amplify, Cognito, Lambda, Step Functions, and AI Core to manage the workflow and user sessions.

The team also used Tiny Fish to gather data behind login walls and Lanfield to score and filter content so token usage could be reduced. Session memory helped the agent keep track of previous interactions and maintain consistency.

The important lessons from this project were:

* Focus on value creation rather than trying to make the technology look perfect
* Teamwork and patience matter a lot under hackathon pressure
* Clear scoping is essential so the team can stay focused on a specific problem

### AI Assistant for IT Architecture Automation

Another team presented an AI assistant that helps engineers decode documents, summarize enterprise requirements, and automatically design IT infrastructure architecture. The system also generated cost estimates and supported Infrastructure as Code scripts.

The main features included:

* Natural language input or document upload
* Automatic architecture design with editable diagrams
* Cost reports and Terraform generation
* Validation steps to keep output consistent and reliable

The solution was built with a layered AWS architecture using a React dashboard, Lambda, and an AI agent core. The team also emphasized tracing and output checking at each step to ensure the workflow stayed logical and aligned with enterprise standards.

This project was especially useful for Solutions Architects because it could save time, improve accuracy, and make the implementation process more transparent when dealing with urgent or complex requests.

### AI Camera-Based Crowd Monitoring and Public Security

One team developed a public monitoring system that used AI to analyze people flow from cameras in places such as airports and supermarkets. The goal was to measure crowd density, detect congestion, and help teams react faster with the right staffing and coordination.

The technical setup included:

* YOLOv26 for object detection and tracking
* Fixed zones on the camera frame for observation
* Agent memory to keep track of people IDs over time
* AI analysis to estimate waiting time and suggest crowd-handling actions

The system architecture used AWS Fargate for video stream processing, DynamoDB and S3 for data storage, and a dashboard for monitoring staff to interact with the AI agent through a chat interface.

The team also faced practical demo challenges such as unstable network conditions and camera placement limitations. Working through those issues showed how important real coordination is when combining AI, backend, frontend, and computer vision work.

### AI for Anti-Money Laundering in Banking

The Six Piller team presented an AI system for investigating and analyzing suspicious financial transactions related to anti-money laundering. The goal was to improve alert handling and reduce false positives, which are a major pain point in banking.

The problem is significant because banks receive millions of alerts every day, and false positive rates can reach 90 to 95 percent. That creates heavy costs in both time and staff effort.

Their solution used a multi-agent approach with:

* KYC profile checking
* Money flow analysis
* Sanction list checking
* Evidence building

They also used a boosted tree model such as CatBoost, which fits structured tabular banking data well. The process was organized into three layers:

* Fast detection through streaming data
* Deep analysis through step functions and specialized agents
* Case management with human review and approval

The project showed how AI can speed up banking investigations from days to hours or even minutes, while still keeping human-in-the-loop control and strong monitoring through AWS tools like CloudWatch and X-Ray.

## Key Takeaways

### Teamwork Matters Most

Hackathons are not won by individual talent alone. Clear role division, shared responsibility, and the ability to work calmly as a team make a huge difference.

### Scoping Is Critical

A focused scope helps teams avoid getting lost in too many ideas and makes it more realistic to deliver a working demo on time.

### Demo Value Beats Perfect Polish

A strong demo that solves a real problem is often more convincing than a technically perfect but less useful concept.

### AI Needs Human Judgment

AI can support many workflows, but humans are still essential for review, decision-making, and responsibility.

### Practical Learning Is Irreplaceable

Hackathons provide a kind of learning that classrooms cannot fully replace: fast iteration, real teamwork, and direct exposure to implementation pressure.

## Applying to Study and Work

The event showed that AI can be applied across very different industries, from retail and business strategy to architecture, public safety, and banking compliance. That makes it clear that technical skills become much more valuable when they are connected to a real business problem.

For my own study path, I can apply the event's lessons by improving my understanding of AI system design, cloud architecture, data flow, observability, and deployment patterns. It is also important to practice scoping problems carefully before starting to build.

For teamwork and career growth, the event reminded me to communicate clearly, stay calm under pressure, and be willing to learn from others. Those habits help in hackathons, university projects, and real work environments alike.

## Personal Reflection

This hackathon was valuable because it showed how AI ideas become real products when they are paired with the right architecture and teamwork. Each project solved a different problem, but all of them shared the same core lesson: good solutions must be practical, focused, and usable.

The most memorable part for me was the balance between innovation and responsibility. AI can move quickly and create impressive results, but people still need to validate the output, manage the risks, and keep the system reliable.

After the event, I felt more motivated to keep building, keep experimenting, and keep improving both my technical ability and my teamwork skills.

## Conclusion

Overall, the Hackathon Aentic AI Bwick was an inspiring and practical event that highlighted how AI can be used to solve real-world problems across multiple domains.

The biggest lesson from the event is that successful technology projects come from a combination of creativity, teamwork, scoping, technical execution, and human judgment. AI is powerful, but the best results still come from people who know how to build with purpose.
