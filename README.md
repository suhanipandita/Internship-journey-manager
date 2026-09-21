# Internship Journey Manager

A browser extension and web app that captures your internship applications automatically and tells you what to do next.

> **Status:** Early development. Nothing is usable yet.

## The problem

Students often apply to 50-100+ internships across LinkedIn, company career portals, referrals, and college drives. Deadlines, assessments, interviews, and follow-ups end up scattered across emails, spreadsheets, and browser tabs. Existing trackers record applications but leave the student to decide what to do next.

## The idea

**Discover → Capture → Track → Prioritize → Act**

- **Browser extension:** detects a job posting, extracts the details, and saves it with one click.
- **Web app:** keeps every application and its upcoming events in one place.
- **Next Best Action engine:** ranks what needs attention today and explains why.

The student shouldn't have to maintain the tracker manually. The system maintains it and says what to do next.

## MVP scope

**Extension**
- Job detail extraction (company, role, location, deadline, description)
- One-click save with review and edit before saving
- "Did you apply?" prompt to confirm submission

**Web app**
- Authentication
- Application list and Kanban views
- Events on applications (deadlines, assessments, interviews, follow-ups)
- Resume management
- "Today" page with ranked next actions and reasons
- Email reminders for upcoming and overdue events
- Basic analytics

**Not in the MVP:** Gmail integration, calendar sync, automatic submission detection, placement-cell features, mobile app.

## Planned tech stack

| Area | Choice |
| --- | --- |
| Web app | Next.js, TypeScript, Tailwind CSS |
| Database, auth, storage | Supabase (Postgres) |
| Browser extension | WXT or Plasmo, React (Chrome first) |
| AI | Claude API (server-side only) |
| Email | Resend |
| Hosting | Vercel |

## Roadmap

- [ ] **Phase 0:** Extension feasibility spike, data model, project setup
- [ ] **Phase 1:** Web app core (auth, applications, events)
- [ ] **Phase 2:** Next Best Action engine (rule-based)
- [ ] **Phase 3:** Browser extension
- [ ] **Phase 4:** AI features (JD summary, resume-job match)
- [ ] **Phase 5:** Notifications, analytics, beta testing

## Repository structure

Planned layout (will be filled in as the project grows):

```
/
├── apps/
│   ├── web/          # Next.js web app
│   └── extension/    # Browser extension
├── docs/             # PRD and design notes
└── README.md
```

## Getting started

Setup instructions will be added once the project scaffold is in place.

## Documentation

- [Product Requirements Document](https://docs.google.com/document/d/e/2PACX-1vTF4P6Ju1lP0mvIAJSljJAq6cFtyufw1S1dZZ6XCKg1LlbRy6coFkEhJnuDd6WUpVqDQOue0fwagkWa/pub)

## License

To be decided.
