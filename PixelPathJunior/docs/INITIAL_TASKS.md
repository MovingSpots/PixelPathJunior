# Initial GitHub Project tasks

Create one repository issue per task below. These are planned tasks, not completed work. The PPJ identifiers are planning references; GitHub will assign its own issue numbers. Initially set every task to **Todo**, and update only when its real state is known.

Project: **PixelPath Junior Capstone**  
Owner: **MovingSpots**, if this remains your GitHub account  
Board: **Todo → In Progress → Review → Done**

Use custom fields **Stage** (single select), **Priority** (single select), and **Target Day** (number). Suggested Stage values: Planning, Backend, Frontend, Review, Testing, Submission. Priority values: High, Medium, Low. Course days are not calendar dates.

## Backlog overview

| ID | Issue title | Stage | Target Day | Priority |
| --- | --- | --- | --- | --- |
| PPJ-01 | Record instructor approval of proposal | Planning | 5 | High |
| PPJ-02 | Create repository and configure task board | Planning | 10 | High |
| PPJ-03 | Configure local development environment | Planning | 10 | High |
| PPJ-04 | Design database schema and sample lessons | Backend | 20 | High |
| PPJ-05 | Build PHP lesson and activity API | Backend | 25 | High |
| PPJ-06 | Build PHP progress API | Backend | 30 | High |
| PPJ-07 | Validate and verify backend requests | Backend | 35 | High |
| PPJ-08 | Build Angular app shell and navigation | Frontend | 40 | High |
| PPJ-09 | Complete instructor code review on Day 40 | Review | 40 | High |
| PPJ-10 | Implement Computer Parts activity | Frontend | 45 | High |
| PPJ-11 | Implement Mouse and Touch activities | Frontend | 50 | High |
| PPJ-12 | Implement Keyboard Fun activity | Frontend | 50 | High |
| PPJ-13 | Implement Patterns and Steps activities | Frontend | 55 | High |
| PPJ-14 | Add spoken prompts and consistent feedback | Frontend | 55 | Medium |
| PPJ-15 | Add progress and badges view | Frontend | 60 | High |
| PPJ-16 | Complete instructor code review on Day 60 | Review | 60 | High |
| PPJ-17 | Build parent or teacher progress view | Frontend | 65 | High |
| PPJ-18 | Refine responsive layouts and accessibility | Testing | 70 | High |
| PPJ-19 | Verify complete user flows and fix defects | Testing | 75 | High |
| PPJ-20 | Finish README and project documentation | Submission | 75 | High |
| PPJ-21 | Complete AIReflection.md | Submission | 75 | High |
| PPJ-22 | Record and submit demonstration video | Submission | 79 | High |
| PPJ-23 | Prepare final demonstration and code review | Submission | 80 | High |

## Issue descriptions and completion checklists

Copy the title and corresponding checklist into each issue. Set Assignee to your own account and select the capstone Project.

### PPJ-01 Record instructor approval of proposal

Stage: Planning | Priority: High | Target Day: 5

- [ ] Attach or link the submitted proposal.
- [ ] Record approval or requested changes without assuming approval.
- [ ] Update agreed scope in README.

### PPJ-02 Create repository and configure task board

Stage: Planning | Priority: High | Target Day: 10

- [ ] Upload README and starter documents.
- [ ] Create and link the GitHub Project.
- [ ] Add the initial task issues and set statuses.

### PPJ-03 Configure local development environment

Stage: Planning | Priority: High | Target Day: 10

- [ ] Verify Git, PHP, and MySQL are available.
- [ ] Confirm XAMPP Apache and MySQL run locally.
- [ ] Prepare VS Code and the tools needed for Angular.
- [ ] Document working local setup and tool versions.

### PPJ-04 Design database schema and sample lessons

Stage: Backend | Priority: High | Target Day: 20

- [ ] Define lesson, activity, learner profile, and progress data.
- [ ] Add a repeatable schema and fictional seed data.
- [ ] Document relationships and why each table is needed.

### PPJ-05 Build PHP lesson and activity API

Stage: Backend | Priority: High | Target Day: 25

- [ ] Return valid JSON lesson and activity data.
- [ ] Handle missing IDs with clear response codes.
- [ ] Keep database access separate from request handlers.

### PPJ-06 Build PHP progress API

Stage: Backend | Priority: High | Target Day: 30

- [ ] Save activity attempts and completion per demonstration profile.
- [ ] Retrieve saved progress after a page refresh.
- [ ] Avoid awarding a badge repeatedly for the same completion.

### PPJ-07 Validate and verify backend requests

Stage: Backend | Priority: High | Target Day: 35

- [ ] Use prepared SQL statements and validate IDs and submitted values.
- [ ] Test valid, invalid, and missing inputs.
- [ ] Handle database errors without exposing credentials.
- [ ] Record API verification results.

### PPJ-08 Build Angular app shell and navigation

Stage: Frontend | Priority: High | Target Day: 40

- [ ] Create Home, activity, badges, and adult-view routes.
- [ ] Connect the interface to the PHP API.
- [ ] Apply the agreed PixelPath Junior design style.
- [ ] Show useful loading and error states.

### PPJ-09 Complete instructor code review on Day 40

Stage: Review | Priority: High | Target Day: 40

- [ ] Prepare a working backend and available interface demonstration.
- [ ] Record instructor feedback and questions.
- [ ] Create follow-up issues for required corrections.

### PPJ-10 Implement Computer Parts activity

Stage: Frontend | Priority: High | Target Day: 45

- [ ] Show correctly labeled monitor, keyboard, mouse, and tower.
- [ ] Allow the child to identify parts with clear feedback.
- [ ] Record completion using the progress API.

### PPJ-11 Implement Mouse and Touch activities

Stage: Frontend | Priority: High | Target Day: 50

- [ ] Implement a click or tap target activity.
- [ ] Add a simple movement or dragging activity.
- [ ] Verify mouse and touch operation and repeat attempts.

### PPJ-12 Implement Keyboard Fun activity

Stage: Frontend | Priority: High | Target Day: 50

- [ ] Accept physical and on-screen keyboard input.
- [ ] Use accurate letter layout and an age-appropriate prompt.
- [ ] Show correct and retry feedback and save completion.

### PPJ-13 Implement Patterns and Steps activities

Stage: Frontend | Priority: High | Target Day: 55

- [ ] Add a simple AB repeating pattern with an unambiguous answer.
- [ ] Add a short sequence-ordering activity.
- [ ] Verify answers, retry feedback, and saved completion.

### PPJ-14 Add spoken prompts and consistent feedback

Stage: Frontend | Priority: Medium | Target Day: 55

- [ ] Provide optional spoken instructions on each activity.
- [ ] Allow prompts to be replayed without overlapping audio.
- [ ] Keep written instructions usable when speech is unavailable.
- [ ] Use encouraging, clear success and retry messages.

### PPJ-15 Add progress and badges view

Stage: Frontend | Priority: High | Target Day: 60

- [ ] Calculate progress from saved completions.
- [ ] Award badges using documented rules.
- [ ] Keep achievements individual without public rankings.

### PPJ-16 Complete instructor code review on Day 60

Stage: Review | Priority: High | Target Day: 60

- [ ] Demonstrate the four activity areas and saved progress.
- [ ] Record feedback and create follow-up issues.
- [ ] Verify and document corrections before final testing.

### PPJ-17 Build parent or teacher progress view

Stage: Frontend | Priority: High | Target Day: 65

- [ ] Show completed activities and areas needing practice for each demo profile.
- [ ] Allow an adult to choose activities.
- [ ] Define and test access to adult controls appropriate to the prototype.

### PPJ-18 Refine responsive layouts and accessibility

Stage: Testing | Priority: High | Target Day: 70

- [ ] Verify desktop and mobile layouts do not clip controls.
- [ ] Use readable contrast, large controls, and visible focus.
- [ ] Check keyboard navigation and labels.
- [ ] Offer tap selection where dragging alone would prevent completion.

### PPJ-19 Verify complete user flows and fix defects

Stage: Testing | Priority: High | Target Day: 75

- [ ] Test all activities, retry cases, and navigation.
- [ ] Verify progress survives refresh and remains separate by profile.
- [ ] Test unavailable API and audio cases.
- [ ] Record expected and actual results in docs/TESTING.md.
- [ ] Resolve or document remaining defects.

### PPJ-20 Finish README and project documentation

Stage: Submission | Priority: High | Target Day: 75

- [ ] Add actual installation, database, API, and frontend run steps.
- [ ] Add design screenshots, architecture notes, and test evidence.
- [ ] Update feature status and known limitations accurately.
- [ ] Verify a fresh setup using the documented steps.

### PPJ-21 Complete AIReflection.md

Stage: Submission | Priority: High | Target Day: 75

- [ ] Replace temporary headings with the instructor exact three questions.
- [ ] Describe AI assistance actually used, including an example.
- [ ] Explain what was verified, corrected, and learned.
- [ ] Commit the finished reflection to the repository.

### PPJ-22 Record and submit demonstration video

Stage: Submission | Priority: High | Target Day: 79

- [ ] Record a 3–5 minute walkthrough of the main features.
- [ ] Include saved progress and the adult view.
- [ ] Verify the video and any shared link can be opened.
- [ ] Submit through Teams before Day 80 and record submission evidence.

### PPJ-23 Prepare final demonstration and code review

Stage: Submission | Priority: High | Target Day: 80

- [ ] Confirm the final code is pushed and the README is current.
- [ ] Practise explaining architecture, decisions, debugging, and learning.
- [ ] Have the project, reflection, and demonstration evidence ready.
- [ ] Demonstrate requested functionality during the final review.

## Task movement

- Todo: the work has not started.
- In Progress: work is active; keep only one or two tasks here at a time.
- Review: checklist and relevant verification are complete; review is pending.
- Done: the change has been reviewed, recorded in Git, and verified.

Backend tasks 4–7 precede the API-connected frontend. Tasks 10–14 precede the final progress and adult view. Instructor reviews are schedule checkpoints. Keep bugs and instructor corrections as additional issues rather than losing them in comments.
