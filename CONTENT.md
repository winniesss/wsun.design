# Portfolio Content, Master Edit File
> Edit text here, then tell Claude to "sync CONTENT.md to the site" to push changes live.
> Images are shown as placeholders, to swap an image, replace the filename in the src tag on the actual page.

---

# PAGE: index.html (Homepage)

## Hero

**Headline line 1:** Making products people love.
**Headline line 2:** Building AI they trust.

**Subtext:**
Hi, I'm Winnie, a Product Designer & Builder with 8+ years at Amazon, AWS, and LivePerson. I design and build AI-powered experiences, shipped products, and design systems that amplify people rather than replace them.

**CTA buttons:** View work | Resume

---

## Stats Bar

- **358%**, Revenue growth at The Silverberg Academy
- **13%**, SCAT score improvement at AWS (~$2.8M pipeline)
- **30%**, Time-to-hire reduction at LivePerson

---

## Project Cards (homepage grid)

### AWS Project Libra
- **Category:** Product Design · Amazon Web Services
- **Title:** AWS Project Libra
- **Description:** Inclusive hybrid meeting system, AI assistant, join flow redesign, accessibility-first. 13% SCAT improvement, $2.8M pipeline.

### LivePerson
- **Category:** Product Design · LivePerson
- **Title:** AI Career Site & Dashboard
- **Description:** Resume-based AI matching + recruiter analytics. 97% candidate advancement, 25K+ monthly traffic.

### Joyrun
- **Category:** Product Design · Joyrun
- **Title:** Social Fitness App
- **Description:** Gamification system for 80M+ users, real-time PvP competition, ranking, motivation loops.

### Mind Flux
- **Category:** AI Product · Solo Builder
- **Title:** Mind Flux
- **Description:** Stoic mental health app that reduces cognitive overload. 30+ beta users. Built with Cursor + Claude Code.

### ReferLink
- **Category:** AI Product · Solo Builder
- **Title:** ReferLink
- **Description:** AI job referral marketplace, autonomous job discovery, semantic matching, resume tailoring. Runs 24/7.

### Tiny Closet
- **Category:** AI Product · Solo Builder
- **Title:** Tiny Closet
- **Description:** AI wardrobe assistant for kids. Photo-to-catalog in seconds. Built in React Native.

---

## "Now" / About Teaser Section

**Label:** NOW
**Headline:** Open to the right opportunity.

**Para 1:**
I'm based in Seattle and actively looking for senior product design roles at companies building meaningful AI products, especially in enterprise productivity, mental health, or tools that make complex systems feel simple.

**Para 2:**
I'm particularly interested in companies where design has a real seat at the table: where research shapes strategy, where accessibility is a requirement not a checkbox, and where building and shipping is expected of the design team.

---

## Footer (all pages)

**Email:** litingsun312@gmail.com
**Links:** LinkedIn · Home · Art · About

---
---

# PAGE: pages/aws.html

## Header
- **Label:** Product Design · Amazon Web Services · 3 Years
- **Title:** AWS Project Libra
- **Subtitle:** Inclusive hybrid meeting system bridging remote and in-person participants, AI meeting agent, join flow redesign, enterprise design system.

## Meta
- **Role:** Product Designer
- **Scope:** End-to-end: join, in-meeting, exit
- **Timeline:** 3 years
- **Research:** 30+ validation studies

## Stats
- **13%**, SCAT score improvement (~$2.8M pipeline)
- **85+**, NPS during AI meeting agent beta
- **3,151+**, In-room participants across 477+ meetings

---

![aws-hero.png](../images/aws-hero.png)

---

## The Problem

When I joined the AWS hybrid meeting system team, the brief was clear: "Make the hybrid meeting experience better." After shadowing 15 team meetings in the first month, I noticed remote participants could see and hear fine, but they couldn't *participate* fine.

In a 10-person meeting with 7 in-room and 3 remote: in-room participants made eye contact, read body language, and jumped into conversations fluidly. Remote participants watched a static wide-angle shot of the room, waited for awkward pauses, and were frequently talked over. The meeting effectively ran as if the remote people weren't there.

**The three tensions we had to resolve:**
- Remote vs. in-room satisfaction (individual tiles gave remote +40 NPS but in-room -20 NPS)
- Equity vs. adoption (individual cameras solved equity but created in-room discomfort)
- AI adoption vs. privacy concerns (83.9% wanted AI summaries, but 13% rejected engagement analysis as "frightening")

---

![aws-gallery-view.png](../images/aws-gallery-view.png)

---

## One Deep Dive, Designing the AI Meeting Agent

With only two months to deliver a working demo, the challenge was not just introducing AI into meetings, but determining when it should speak, and when it should stay silent.

**Business pressure:** this was 2023. Every competitor was shipping AI engagement features. Leadership asked why we weren't leveraging ML capabilities.

### Key Constraints
- Designing within an existing component library for speed and consistency
- Integrating summaries from third-party platforms, Zoom, Teams, Chime
- Connecting to user identity and authorization models
- Filtering non-essential information to prevent cognitive overload
- Designing for neurodiverse participants with accessibility-first approach

### Decision Approach

Given the compressed timeline, I focused on delivering a grounded experience rather than exploring speculative AI behaviors, emphasizing clarity, relevance, and participant control. This meant intentionally rejecting several ideas that introduced unnecessary automation or surfaced information without strong context.

I partnered closely with PM and engineering to define feasible demo scope, while coordinating with third-party teams to understand platform constraints early. In parallel, I conducted targeted user conversations to validate what level of AI intervention felt supportive rather than intrusive.

**The outcome:** Demoed and shipped the AI meeting agent in 2 months. Trust remained high, beta program NPS stayed above 85. VP endorsement: "This is better than our OP1 executive rooms, can we deploy in all leadership spaces?"

---

![aws-tv-ai.png](../images/aws-tv-ai.png)

---

## Design Impact

- Drove product strategy that convinced leadership to bet against industry convention based on user research data (individual cameras vs. single wide-angle)
- Built the AI meeting agent for tablet and TV surfaces, demoed and shipped in 2 months, NPS stayed above 85 throughout beta
- Built the design system with **400+ components**, providing guidelines and documentation for both design and engineering teams to ship consistently at scale
- Designed the onboarding and welcome meeting join flow, reducing friction for first-time users entering hybrid meetings
- Established primary/secondary display model that reduced cognitive load across all users
- Conducted and synthesized 40+ in-person usability tests with monthly research cadence

---

![aws-screen1.png](../images/aws-screen1.png)
![aws-screen2.png](../images/aws-screen2.png)
![aws-screen3.png](../images/aws-screen3.png)

---

## Accessibility

- Led accessibility audit and ensured Born Accessible compliance from day one
- Designed for neurodiverse users (ADHD, autism), low vision, deaf/hard of hearing, and physical disabilities
- **100% of accessibility users preferred Libra over traditional conference rooms**
- Designed customizable captions, content zoom/pinch, and consistent information placement as core product features
- Ran accessibility workshops to educate engineers on design principles

## Design System

Scaled the enterprise design system to 400+ responsive components across Web, Mobile, and TV surfaces. Reduced engineering implementation time and ensured WCAG compliance across the suite.

Created primary display (tablet) for active content and secondary display (TV) for passive reference, reducing split attention that particularly impacted neurodiverse users.

---
---

# PAGE: pages/liveperson.html

## Header
- **Label:** Product Design · LivePerson · May 2021 – Sep 2022
- **Title:** AI-Enabled Career Site & Recruiting Dashboard
- **Subtitle:** Resume-based AI matching + analytics dashboard that reduced candidate screening time by 71% and drove 97% recruiter advancement of AI-matched candidates.

## Meta
- **Role:** Design Lead
- **Timeline:** May 2021 – Sep 2022

## Stats
- **25K+**, Monthly traffic
- **NPS +80**
- **97%**, AI-matched candidates advanced by recruiters
- **18%**, Conversion: resume upload to role application
- **94%**, Bot engagement rate among Smart Apply users

---

![liveperson-hero.jpg](../images/liveperson-hero.jpg)

---

## The Challenge

The brief was straightforward: "Design a better career site that uses our conversational AI technology." But that framing missed the real problem.

- **Candidates:** Spent hours searching job boards but couldn't find roles that matched their background
- **Recruiters:** Manually screened hundreds of applications, 71% of poorly-scored candidates sat in queue for 6+ days
- **Business:** Startup churn of 26% meant constant hiring pressure, with each bad hire costing 6-9 months' salary

**The insight that changed the strategy:** AI matching only works if candidates trust the recommendations. And they won't trust recommendations unless they understand *why* those roles match their background.

This meant we couldn't just build "submit resume, get matches", we needed to design for **transparency and control**.

---

## One Deep Dive, Resume Upload First, Search Second

Every major job site (LinkedIn, Indeed, Glassdoor) puts search first and profile-building second. Users are trained to search for jobs, not upload resumes and wait for recommendations.

**My position:** If AI matching is our value proposition, we need to prove it works before letting users fall back to manual search.

### What I proposed
- Make "Match your resume to a role" the primary CTA on the homepage
- Search bar visible but secondary
- After upload, show *why* each role matched, skills highlighted, experience level match explained

### PM pushback & how I responded
**PM:** "Users expect to search immediately. If we gate-keep search behind resume upload, we'll lose them."

**My counter:** We ran A/B tests. Version A (2 CTAs: Search + Match Resume) had better engagement on search but worse conversion to apply. Version B (3 CTAs: Search + Match Resume + Talk to Concierge) had the best overall conversion because it gave users multiple entry points based on intent.

**The data that convinced leadership:**
- Users who uploaded resumes first applied at **18% conversion**
- Users who searched first applied at **7% conversion**

AI recommendations worked, but only if users engaged with them before forming search habits.

---

![liveperson-screen1.png](../images/liveperson-screen1.png)

---

## What We Shipped

**For Candidates**
- AI-powered resume matching with transparent "why this role?" explanations
- Conversational bot for instant Q&A (94% of applicants used it)
- Location-aware recommendations
- Quick search with 14K+ filter uses (most popular: "Remote")

**For Recruiters**
- Dashboard showing real-time metrics across all open roles
- Candidate grading (A/B/C/D) with full transparency into AI scoring
- One-click integration with Greenhouse ATS
- Sort by "Last Contact" to reduce response wait time

---

![liveperson-screen2.png](../images/liveperson-screen2.png)

---

## Business Impact

- 25K+ monthly traffic to career site, +80 NPS
- 32K+ quick searches delivering 2.1M+ results
- **97% of AI Smart Matched candidates advanced by recruiters**
- 52% of candidates advanced by hiring managers post-dashboard launch
- 71% faster action on low-scoring candidates (previously sat for weeks)
- 1,000+ AI-matched placements, 47% applied for recommended roles

---
---

# PAGE: pages/joyrun.html

## Header
- **Label:** Product Design · Joyrun
- **Title:** Social Fitness & Gamification Design
- **Subtitle:** Redesigning engagement for Joyrun, a social running platform with 80M+ users across 2,100 cities. Built real-time PvP competition, ranking systems, and gamified motivation loops to drive retention.

## Meta
- **Role:** Product Designer, User Researcher
- **Timeline:** 4 months
- **Team:** 3 UX + 2 UI designers
- **Tools:** Sketch, Figma, Protopie

## Stats
- **80M+**, Users on platform
- **2.1K+**, Cities worldwide
- **20K+**, Registered running groups

---

![joyrun-01.png](../images/joyrun/joyrun-01.png)

---

## The Challenge

Joyrun's PM identified declining user engagement, runners were completing runs but not returning. Market research surfaced three root causes: lack of competitive motivation, no social accountability, and missing real-time feedback during runs.

Our brief: design a gamification system that would increase stickiness without alienating casual users.

## Understanding Users

We conducted 20+ quantitative surveys and 5+ qualitative interviews, synthesizing three distinct runner personas:

- **Alice, Beginner Runner:** Struggles with finding motivation to start. Needs encouragement and low-stakes entry points.
- **Jack, Intermediate Runner:** Goes to the gym 2–3x/week. Motivated by personal records and friendly competition.
- **Chloe, Advanced Runner:** Runs 40+ miles/week. Driven by performance data, rankings, and external challenges.

---

![joyrun-02.png](../images/joyrun/joyrun-02.png)

---

## The Solution: Competition Mechanism

After mapping user pain points to design opportunities, we narrowed to three feature concepts, and used a gamification value matrix to prioritize them:

- **Ranking Run, Real-time PvP:** challenge other users using your recorded runs
- **Challenge Run, Daily system-generated challenges and limited-time events**
- **Quick Run, A lightweight portal to encourage spontaneous runs**

Ranking Run emerged as Priority 1, highest impact across motivation, social accountability, and retention.

---

![joyrun-03.png](../images/joyrun/joyrun-03.png)
![joyrun-04.png](../images/joyrun/joyrun-04.png)

---

## Ranking Run: 3-Step Flow

### Step 1, Preparing
Users choose to **attack** (challenge others using their best records) or **defend** (stay open to incoming challenges). Modal popup screens keep focus on the task. Clear attack/defend framing makes the competitive stakes legible at a glance.

### Step 2, Matching
The system auto-matches competitors of similar rank within the selected time window. Users have 5 seconds to accept or decline, creating urgency without pressure. Seasonal resets (every 8 weeks) give all players a fresh chance to climb the ladder.

### Step 3, Warm-up & Running
Safety first: warm-up is required before competition begins. During the run, users see competitor positions in real-time. Red/green color coding signals whether they're ahead or behind. One-handed lock and pass buttons keep interaction minimal while running.

---

![joyrun-09.png](../images/joyrun/joyrun-09.png)
![joyrun-11.png](../images/joyrun/joyrun-11.png)
![joyrun-12.png](../images/joyrun/joyrun-12.png)
![joyrun-14.png](../images/joyrun/joyrun-14.png)

---
---

# PAGE: pages/mindflux.html

## Header
- **Label:** AI Product · Solo Designer & Builder · 30+ Beta Users
- **Title:** Mind Flux, Stoic Triage for the Modern Mind
- **Subtitle:** Mobile-first mental health app that reduces cognitive overload through friction-free capture and psychology-informed interactions. A bridge between productivity and psychotherapy, built solo using Cursor, Claude Code, and Gemini.

## Meta
- **Role:** Solo Designer & Builder
- **Status:** Private beta, 30+ users
- **Tools:** Cursor, Claude Code, Gemini
- **Demo:** [Live demo →](https://flux-276724819964.us-west1.run.app/)

---

![mindflux-01.png](../images/mindflux/mindflux-01.png)

---

## The Problem

Mental health apps add cognitive load when users are already overwhelmed. Traditional to-do lists require upfront categorization. Mental health apps require journaling prompts. Both create decision fatigue at exactly the wrong moment, when someone is already stressed.

Could AI help separate "things I can control" from "things I can't"? And would visualizing that separation actually feel relieving?

## The Approach

- **Zero-Friction Capture**, Single-tap voice or text, no required fields, one-handed mobile use during stress
- **Psychology-Informed Interactions**, Swipe-based triage based on Stoic philosophy's Dichotomy of Control
- **Trust Through Craft**, Calm-tech aesthetic with fluid animations, visual language that communicates safety

**The core mechanic, Physical gesture = psychological relief**
- Swipe left ("Let Them"): Uncontrollable worries dissolve with satisfying visual feedback
- Swipe right ("Let Me"): Actionable items gain visual weight and clarity

The physical gesture creates agency. The visual effect provides dopamine reinforcement for healthy behavior.

---

## The Swipe System

![mindflux-02.png](../images/mindflux/mindflux-02.png)

Users know intellectually what they can and can't control, but anxiety doesn't respond to logic, it needs a physical release mechanism.

When users swipe left to "Let Them," uncontrollable worries dissolve with satisfying visual feedback. Users can revisit the gallery to see their worries in perspective, accompanied by relevant philosophy quotes (Seneca: "We suffer more often in imagination than in reality").

**The Cleanse Gallery feature:** When users are ready to permanently let go, they can clear the gallery, providing a final ritual of release.

**The psychology:**
- Cognitive reframing: AI helps users see worries from a healthier perspective
- Evidence of progress: The gallery shows how many worries users have successfully released
- User control: The "cleanse" action gives users agency over their mental space
- Ritual completion: Clearing the gallery provides closure and reinforcement

---

## The "Let Me" Flow, Converting intent into time-bound commitment

Most to-do apps fail because users add tasks but never commit to doing them. The act of capturing feels productive, but without commitment timing, tasks sit forever in a generic list, creating guilt and disengagement.

### Step 1, Triage with context
AI reframe appears before asking for commitment, priming users with positive motivation so they understand WHY this task matters before being asked WHEN they'll do it.

### Step 2, Low-friction commitment
Three choices only: TODAY, TOMORROW, THIS WEEKEND. No "Someday" option, forces real commitment. Limited choices reduce decision fatigue. Large 44pt touch targets.

### Step 3, Confirmation & visibility
Task appears in Commitments with date and checkbox. Subtle "Added to actions" toast with Undo. Seeing it visualized reinforces the decision and adds accountability.

![mindflux-07.png](../images/mindflux/mindflux-07.png)
![mindflux-08.png](../images/mindflux/mindflux-08.png)
![mindflux-09.png](../images/mindflux/mindflux-09.png)

> "Offloading provided immediate relief, users felt lighter within 30 seconds, before even organizing tasks.", Beta user research finding

---

## V2, Research-Driven Evolution

### What therapists revealed
After beta launch, I interviewed licensed therapists to validate my therapeutic approach. What I learned changed everything.

- 70% of therapy clients struggle with work/relationship burnout or ADHD, validating my target audience but revealing I was solving the wrong problem
- ADHD users need task decomposition, breaking overwhelming projects into micro-tasks with time anchoring (weak time perception means tasks without committed times never happen)
- AI can replace therapy workflows, breaking down tasks into subtasks, scheduling prompts at capture, pattern detection for when professional intervention is needed

**Before V2:** Users manually added tasks one-by-one. Required upfront categorization. No automatic breakdown or scheduling. Desktop-focused. Result: more cognitive load, not less.

**After V2:** AI-powered "Nebula Input", voice/text brain dump. Auto-parses thoughts into bubbles. Automatic task breakdown + time anchoring. Mobile-first, one-handed design. Native calendar sync.

---

![mindflux-05.png](../images/mindflux/mindflux-05.png)

---

## Outcomes

- **85%**, Scheduling completion: Progressive disclosure reduced decision fatigue, 85% of users completed the scheduling flow.
- **92%**, Mobile captures: 92% of captures happened on mobile during stress moments, validating the mobile-first approach.
- **3x**, Task completion: Calendar integration drove 3x higher task completion vs. in-app-only reminders.

**Key Learning:** AI excels at task decomposition and time anchoring, but emotional reframing requires human expertise. This revealed a hybrid care model opportunity: app handles structure, therapists handle complexity.

## What's Next

- Integrate pre-therapy assessment (PHQ-9, GAD-7) triggered when AI detects distress patterns
- Build therapist referral directory with direct booking
- Test "warm handoff" protocol: app shares anonymized user patterns to reduce first-session intake time by 50%
- Partner with 2–3 clinics to pilot B2B2C model through corporate wellness programs

---
---

# PAGE: pages/referlink.html

## Header
- **Label:** AI Product · Solo Designer & Builder
- **Title:** ReferLink, AI Job Hunting Platform
- **Subtitle:** A two-phase system solving the job search problem: a referral marketplace connecting job seekers with employees, layered with an AI agent that autonomously scrapes jobs, matches semantically, tailors resumes, and runs your search 24/7.

## Meta
- **Role:** Solo Designer & Builder
- **Status:** In development
- **Tools:** Cursor, Claude Code

---

![referlink-05.png](../images/referlink/referlink-05.png)

---

## The Research

While job searching myself, I talked to others going through the same process to understand if my frustrations were universal or just mine. The phrase "hard to find referral opportunities" came up repeatedly. People knew referrals were important, **70% of jobs are filled that way**, but their networks didn't overlap with the companies they wanted to work for.

**The deeper pattern:** job searching takes an enormous amount of time. Most of it is repetitive work: checking job boards, tailoring resumes, searching for connections, tracking applications.

**What job seekers said:**
- "I feel weird asking strangers for help"
- "I lose track of where I applied"
- "I just want someone to tell me the 3 roles to apply to today"

**What referrers said:**
- They'll help strangers, but only with enough candidate info, shaped two-way visibility
- They're worried about spam, influenced limiting simultaneous requests

---

## The Strategy, Solve both problems, but in sequence

**Phase 1, Referral Marketplace + Dashboard**
Connect job seekers with employees who can refer. Give both sides a unified place to track everything. Solve the access problem first, create the infrastructure Phase 2 needs.

**Phase 2, AI Agent (In Development)**
Autonomous job discovery across 50+ sources. Semantic resume tailoring per job. Referral path finding. Application tracking. Runs 24/7, you check the dashboard, not the job boards.

**Why this order, Infrastructure before intelligence**
You can't automate referral discovery without first having a referral network to tap into. Phase 1 creates the infrastructure. Phase 2 adds the intelligence layer on top.

---

![referlink-03.png](../images/referlink/referlink-03.png)

---

## Phase 1, The Marketplace

**For job seekers:**
- Browse employees at target companies willing to refer
- Send low-stakes introduction requests (limit on simultaneous requests reduces spam)
- Track all referral conversations in one dashboard
- Combine with application tracking, one product for the entire search

**For referrers:**
- See full candidate profile before agreeing to refer
- Match score shows why this person fits their company
- Control over who you help, no obligation to refer everyone
- Referral bonus tracking built in

---

## Phase 2, The AI Agent

**What the agent does:**
- **Autonomous job discovery**, continuously scrapes LinkedIn, Greenhouse, Lever, company career pages, detects opportunities within hours of publication
- **Semantic matching**, alerts only to high-priority matches, not every posting
- **Resume tailoring**, AI adapts resume language to match each job description automatically
- **Referral path finding**, identifies employees at target companies who can refer
- **Application tracking**, unified dashboard, status, and follow-ups

**The stickiness insight:** Referrals are episodic, you need one, then you're done until your next job search. The AI agent solves stickiness. If it runs daily and surfaces opportunities, people check the dashboard daily.

---

![referlink-06.png](../images/referlink/referlink-06.png)

---

## Design Principles, Transparency at every step

- **For candidates:** See exactly why each job was matched. Control the search parameters. Review and approve before anything is sent.
- **For referrers:** See candidate profile, match score, and why this person was selected for their company, before agreeing to refer.
- **For both:** Human review at every critical step. AI does the legwork, humans make the decisions.

## What I Learned

- **Business strategy means thinking beyond features**, Building a two-sided marketplace forced me to think about retention, not just functionality.
- **Rapid prototyping ≠ shipping a real product**, Lovable got me to a working prototype in days. Building the actual deployed product took weeks.
- **Build, ship, learn, iterate beats plan, plan, plan.**, Actually putting something in front of users teaches you things interviews can't. Speed to learning matters more than speed to perfection.

---
---

# PAGE: pages/tinycloset.html

## Header
- **Label:** AI Product · Solo Designer & Builder
- **Title:** Tiny Closet, AI Wardrobe for Kids
- **Subtitle:** An AI-powered wardrobe assistant that transforms messy children's clothing collections into organized digital assets and daily styling inspiration for high-bandwidth parents.

## Meta
- **Role:** Solo Designer & Builder
- **Status:** In development
- **Tools:** React Native, Claude AI
- **Target:** Parents of young children

---

![tc-01.png](../images/tinycloset/tc-01.png)

---

## The Problem

Young children (ages 2–8) can go through 2–3 clothing sizes per year. Parents accumulate huge quantities of clothes, hand-me-downs, gifts, seasonal items, that become impossible to manage. The result: every morning is a scramble through disorganized drawers and closets, often ending with mismatched outfits and frustrated parents.

**Pain point 1, Inventory chaos:** Parents don't know what they own. Clothes get buried, forgotten, worn when too small, or missed entirely during laundry cycles.

**Pain point 2, Morning decision fatigue:** Choosing an outfit involves size checks, weather appropriateness, occasion suitability, and the child's preferences, too many variables before 8am.

---

## The Solution, Photograph once. Let AI do the rest.

Parents photograph each clothing item once. AI categorizes it (type, size, color, season, occasion), stores it in a digital wardrobe, and generates daily outfit recommendations based on weather, occasion, and the child's style preferences.

### AI Catalog, Instant classification
Take a photo and AI auto-tags: category, brand, color, season, size. 122 items organized in seconds. Filter by Top, Bottom, Full Body, Romper, Vest, and more.

### Daily Outfits, Weather-aware suggestions
Home screen pulls live weather and surfaces outfit combos in Playful or Chic style. Numbered pieces let parents assemble quickly, no browsing required.

### Closet Stats, Wardrobe intelligence
Visual breakdown of 124 items by category (Top, Bottom, Outerwear, Pajamas…) and top brands (Misha & Puff, Miki House). Know exactly what you own.

---

![tc-02.png](../images/tinycloset/tc-02.png)
![tc-03.png](../images/tinycloset/tc-03.png)

---

## Key Design Decisions, Designing for exhausted parents at 7am

**Local-first privacy:** All photos and data live strictly on the phone's storage, no cloud server stores personal photos. This was a non-negotiable for parents sharing photos of their children. The FAQ answers this directly: "Tiny Closet is 'Local First.' We do not have a cloud server that stores your personal photos."

**Style modes, not rigid rules:** Two outfit modes, Playful and Chic, let parents quickly match the day's vibe without micro-managing every item. The AI adapts to the selected style when composing outfit sets.

**Friction reduction:** Numbered outfit pieces (1, 2, 3) make assembly obvious. Refresh button swaps combinations instantly. Heart saves favorites. Designed for one-handed use while holding a toddler.

**Transparent AI:** FAQ explains exactly how AI makes decisions: "The AI analyzes the sleeve length, fabric weight (visually), and item type. You can always manually adjust these tags." No black box.

---

![tc-04.png](../images/tinycloset/tc-04.png)

---

## What I Built

Tiny Closet is a fully functional React Native app that my family uses daily for my daughter Thea (1Y 3M). The wardrobe has grown to 124 items across 9 categories.

**Features shipped across v1.7 and v1.8:**
- Archive functionality, retire outgrown items without deleting them
- Brand filter in Closet view, quickly surface all Misha & Puff, Miki House, or Organic Zoo items
- Improved crop tool, handles long screenshots better for catalog photos
- Lookbook, saved outfit combinations for recurring occasions
- Export/import backup, preserves the local database when switching phones

> "I removed the 'Find Online' feature to focus on local privacy and speed. Feature scope creep vs. core value, local-first won.", v1.8 product decision

## Learnings

**Lesson 1, Real usage reveals hidden friction:** Daily use exposed issues no user interview would surface, like needing the crop tool to handle long screenshots after parents photograph clothes on hangers.

**Lesson 2, Privacy as a feature, not a constraint:** Local-first became a selling point, not a limitation. Parents with young children are more privacy-sensitive, making "no cloud" a trust builder, not a missing feature.

**Lesson 3, Ship, then cut scope:** Removing "Find Online" in v1.8 was the right call. Every feature that doesn't serve the core need adds cognitive overhead for both users and the builder.
