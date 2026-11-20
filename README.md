# LastCall — A Marketplace for Time-Sensitive Opportunities

**United International University · CSE 3412 System Analysis and Design Lab · Section B · Fall 2026**

Course teacher: Rejwan Ahmed ([@rejwanahmed007](https://github.com/rejwanahmed007))

LastCall addresses a problem shared by sellers with surplus food and people holding unused tickets or vouchers: the opportunity loses its value after pickup, admission, departure, or redemption closes. The proposed marketplace helps holders list eligible opportunities and buyers find and claim them before expiry.

## Project scope

| Stage | Scope and evidence |
|---|---|
| Previous DBMS project | The original project concerns surplus food and event tickets. Its database defines food and ticket listings, events, reservations, orders, payments, and ticket ownership history. These are verified schema elements. [DBMS schema at the inspected revision](https://github.com/aunabil-abtahi/lastcall/blob/2f702af434efbd3f3e9451b657ca90157c63a411/database/schema.sql) |
| Faculty-approved SAD continuation | The team will investigate unused coupons, vouchers, bus tickets, train tickets, and other time-sensitive opportunities. For each category, assess legal transferability, issuer permission, identity restrictions, expiry, and how validity can be checked. Categories without a supported transfer path stay outside the prototype. |
| Prototype scope | The major workflow and supporting minor features are pending team review and the P2 feasibility decision. The expanded categories are proposals. This repository currently contains the project foundation. |

## Team

Three students will each record their role and module ownership in [TEAM.md](./TEAM.md).

## Links

| Resource | Location |
|---|---|
| Active SAD repository | [aunabil-abtahi/lastcall-sad](https://github.com/aunabil-abtahi/lastcall-sad) |
| Previous DBMS project | [aunabil-abtahi/lastcall](https://github.com/aunabil-abtahi/lastcall) |
| Faculty references (course access required) | [Course resources](https://github.com/rejwanahmed007-tutorials/uiu-sad-lab-student-resources) · [Deliverable templates](https://github.com/rejwanahmed007-tutorials/uiu-sad-lab-student-resources/tree/main/templates) |
| Figma prototype · Jira board · live demo | Add the respective links when available. |

## Deliverables and planned repository layout

The dates below are faculty checkpoints. Create each directory with its first project deliverable. Presentation slides are due in the repository and course form by 11:00 AM Dhaka time on presentation day unless faculty announce a change.

| Checkpoint | Faculty date | Expected output | Destination |
|---|---|---|---|
| UI design track | From Nov 12, 2026 | Personas, journey map, wireframes for P2, then clickable hi-fi prototype and usability findings | `docs/04-ui/` |
| P1 · Proposal | Nov 14, 2026 | Stakeholder evidence, weighted benchmark, MoSCoW scope and proposal slides | `docs/01-proposal/` |
| P2 · Feasibility | Nov 21, 2026 | Feasibility report, NPV workbook, major/minor split, context and level-1 DFDs, use cases and wireframes | `docs/02-feasibility/`, `docs/03-design/diagrams/`, `docs/04-ui/` |
| Before Lab 6 | Before the Nov 28, 2026 lab | User stories for each Must and Should feature, domain class diagram, runnable project skeleton and stack choice | `docs/05-srs/`, `docs/03-design/diagrams/`, `src/` |
| Planning and SRS | From Nov 28, 2026 | Jira backlog, critical path schedule and progressive SRS draft | Jira, `docs/02-feasibility/`, `docs/05-srs/` |
| Individual UI exam and sprint check | Dec 19, 2026 | MCQ and Figma exam; team sprint evidence | Figma, Jira and repository |
| P3 · Major prototype 50% | Dec 26, 2026 | At least half the major workflows running with database data, activity and class models | `src/`, `docs/03-design/diagrams/` |
| P4 · Major prototype 100% | Dec 31, 2026 (online) | All major workflows, updated models and at least 10 executed test cases | `src/`, `docs/03-design/diagrams/`, `docs/06-testing/` |
| P5 · Minor prototype 50% | Jan 2, 2027 | At least half the minor features, integration with a major workflow, user acceptance test plan | `src/`, `docs/06-testing/` |
| P6 · Minor prototype 100% | Jan 9, 2027 | Integrated system, security checks, user acceptance results and deployment, migration and training plan | `src/`, `docs/06-testing/`, `docs/07-final-report/` |
| P7 · Final showcase and defense | Jan 16, 2027 | Final SRS, traceability matrix, diagrams, technical report and individual defense; all materials due by 11:00 AM | `docs/05-srs/`, `docs/03-design/diagrams/`, `docs/07-final-report/` |

## How to run

Run instructions will accompany the first runnable SAD prototype in `src/`. The previous DBMS application is linked above.

## Definition of Done

Another team member checks the acceptance criteria and reviews the pull request. A story is done when the reviewed change is merged, tests pass, the project runs from a fresh clone, error cases are handled, and Jira reflects the result.

## Team rules

- Use a branch and a pull request for each change. A teammate reviews before merge.
- Name feature branches `feature/<JIRA-KEY>-short-name`. Follow the faculty commit conventions, such as `feat(<JIRA-KEY>): …`, `fix: …`, `docs: …`, and `design: …`.
- Keep editable diagram sources alongside PNG exports. Keep credentials and local environment files out of version control.

## AI-use disclosure

Each member records actual AI assistance here for work they submit and carries the disclosure into Appendix C of the SRS and the final report. Include the tool, the task it assisted with, and how the member checked the result.
