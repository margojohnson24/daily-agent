# Learning Roadmap

> From personal tool to production product to teaching others.

---

## My Three Goals

### 1. Personal Daily Agent
Build an AI assistant that helps me:
- Manage calendars and tasks intelligently
- Feel productive AND grounded
- Have space to REST (protect boundaries)
- Understand the code structure (objects, logic, data flow)

### 2. Learn AI-Assisted Building
- Learn how to build apps using Claude Code
- Document best practices that help me as a builder
- Create shareable learnings for others (PMs, teams, companies)

### 3. Personal > Production > Multi-User Evolution
- **Stage 1:** Production experience I can safely use (phone + computer)
- **Stage 2:** Connect to tools/APIs (Claude API, Gmail, Google Calendar)
- **Stage 3:** Offer to others (learn auth, tenancy, onboarding)

---

## Stage 1: Personal Production (Weeks 1-2)

*Target: 6-10 hours of building*

### Milestones
- [ ] Core features working (Home, Calendar, Kanban, Tasks)
- [ ] Data persistence (Supabase backend)
- [ ] Deploy to web (Vercel - accessible anywhere)
- [ ] Google Calendar integration (read real calendar)
- [ ] Mobile PWA (install on phone)
- [ ] Voice capture (Wispr Flow > Claude Project > App)

### Technical Concepts to Learn
| Concept | Why It Matters |
|---------|---------------|
| APIs and authentication | How apps talk to each other |
| Frontend vs. backend | What runs in browser vs. server |
| Database design | How data is structured and stored |
| Deployment pipelines | How code becomes a live website |
| OAuth flows | How Google Calendar shares data securely |

---

## Stage 2: Progressive Integrations (Weeks 2-4)

*Target: 2-3 hours per integration*

### Phase A - Read-Only Integrations
- [ ] Google Calendar API (pull real calendar)
- [ ] Weather API (real weather on home screen)
- [ ] Claude API (smarter task categorization)

### Phase B - Two-Way Integrations
- [ ] Gmail API (read emails, extract tasks)
- [ ] Google Calendar Write (create events from tasks)
- [ ] Slack (send task reminders)

### Technical Concepts to Learn
| Concept | Why It Matters |
|---------|---------------|
| API keys and environment variables | Keeping secrets safe |
| Rate limiting and quotas | Respecting API boundaries |
| Webhook patterns | Getting notified when things change |
| Error handling and retries | What happens when things fail |
| Data synchronization | Keeping two systems in agreement |

---

## Stage 3: Multi-User Product (Weeks 4-8)

*Target: 20-40 hours total*

### Week 4-5: Foundation
- [ ] User authentication (email/password)
- [ ] Multi-tenancy (separate user data)
- [ ] User settings/preferences
- [ ] Simple onboarding flow

### Week 6: Polish
- [ ] Invite system (5-10 friends)
- [ ] Help documentation
- [ ] Bug fixes from real users
- [ ] Performance optimization

### Week 7-8: Product Launch
- [ ] Payment integration (Stripe - optional)
- [ ] Marketing landing page
- [ ] Analytics dashboard
- [ ] Feedback system

### Technical Concepts to Learn
| Concept | Why It Matters |
|---------|---------------|
| Authentication vs. authorization | Who you are vs. what you can do |
| Database schema for multi-user | Each user sees only their data |
| Payment processing | Turning a tool into a business |
| User onboarding patterns | First impressions matter |
| Product analytics | Understanding how people use it |
| Customer support tooling | Helping users when things break |

---

## Best Practices (Captured Along the Way)

### 1. Start with Context Files
Teach AI your domain before building. Example: `calendar-context.md` gave Claude the vocabulary of time blocks, categories, and workflow before a single line of code was written.

### 2. Iterate in Public
Don't wait for "perfect." Ship v1 and improve. The first version of this app was a plain task list. Each conversation added a layer.

### 3. Describe Feelings, Not Implementation
"I want it to feel fluid" works better than "Use this specific animation." Let the tool translate intent into code.

### 4. Build for Your Real Workflow
Your actual calendar and categories (Lott House, Berene House, Subaru) make this useful on day one. Generic tools stay generic forever.

### 5. Ask "Why?" When Stuck
Understanding beats blind copying. When something breaks, understanding *why* it broke teaches more than just fixing it.

### 6. Conversational Building
Describe what you want, Claude builds it. Iterate based on what you see and feel. The conversation *is* the development process.

### 7. Progressive Enhancement
Start simple. Add complexity gradually. Each iteration teaches more. This app went from a static HTML list to a conversational AI dashboard in a handful of sessions.

---

## What I Can Teach Others

### For Other PMs
- "How to Build Your First App Without Coding"
- "Product Thinking Applied to AI Tools"
- "From Idea to Production in 30 Days"

### For My Teams
- "How We Use AI to Build Faster"
- "Prototype to Production Patterns"
- "When to Build vs. Buy with AI"

### For My Company
- Internal tools built in hours, not months
- Everyone can prototype ideas
- Reduce dependency on eng for exploration

---

## Learning Arc Timeline

```
Week 1-2    Personal app working
              Understand: frontend, databases, deployment

Week 2-4    Integrations adding superpowers
              Understand: APIs, authentication, data flow

Week 4-8    Multi-user product
              Understand: scaling, business logic, user management

Month 3+    Teaching others
              Document the journey
```

---

## Insights Captured

*Add learnings here as I go.*

### January 25, 2026 - First Build Sessions
- Built a complete task app (Home, Calendar, Kanban, Tasks) in a single HTML file with no dependencies
- Learned: describing the *feeling* of what I want produces better results than specifying technical details
- Learned: iterating in small steps (list > calendar > kanban > chat) keeps momentum and lets me steer
- Learned: giving Claude context about my real life (time blocks, house names, categories) makes the tool immediately personal
- The conversational Home tab came from asking for what I *wished* existed, not what I thought was possible

### [Date] -
-

### [Date] -
-

---

## Current Status

| | |
|---|---|
| **Stage** | Stage 1 - Personal Production |
| **Last Updated** | January 25, 2026 |
| **What's Working** | Home (chat + greeting), Calendar, Kanban (drag & drop), Tasks (categorized with subtags), smart auto-categorization, waiting-on-someone indicator, subtag management |
| **Next Milestone** | Supabase backend for data persistence |
| **Hours Invested** | ~3-4 |
