# PixelPath Junior
Grade 1 computer skills practice web app built with PHP, MySQL, and Angular for my triOS Web Capstone.

A computer skills practice web app for Grade 1 children.

**Developer:** Selvaraj Thyagarajan  
**Course:** MWDWC — Web Capstone, triOS College  
**Repository name:** PixelPathJunior  
**Current stage:** Proposal and interface concepts; implementation planned. Instructor approval must be recorded when received.

## Introduction

PixelPath Junior is a web app designed to help Grade 1 children practise their first computer skills through short, playful activities. Children may be familiar with videos and touchscreens before they are comfortable identifying computer parts, using a mouse and keyboard, or following simple digital instructions. The app will guide them from these basics toward early problem solving with pictures, spoken prompts, and immediate feedback. A parent or teacher will be able to choose activities and review progress.

The project will be developed in stages, starting with a PHP and MySQL backend and adding an Angular interface as the course progresses. React is an optional later alternative, subject to scope and instructor approval.

## General functionality

- Illustrated lessons about computer parts, their uses, and safe device habits.
- Mouse or touch practice through clicking, dragging, matching, and sorting.
- Keyboard activities for letters, numbers, and common keys.
- Early logic activities with visual patterns and steps in order.
- Optional spoken instructions and clear, encouraging feedback.
- Badges for completed lessons and individual progress without public rankings.
- A parent or teacher view of completed activities and skills needing more practice.

These are proposed features, not a claim of completed functionality.

## Initial prototype scope

The first working version will include one usable activity in each of four areas:

| Area | Initial activity |
| --- | --- |
| Computer Parts | Identify the monitor, keyboard, mouse, and computer tower |
| Mouse & Touch | Click or tap a target, then practise moving and dragging |
| Keyboard Fun | Find letters with a physical or on-screen keyboard |
| Patterns & Steps | Complete a simple repeating pattern and arrange steps |

The prototype will also include basic saved progress, badges, spoken prompts, and a simple adult progress view. More lessons can be added after these flows work reliably.

## Planned technology

| Component | Technology |
| --- | --- |
| Backend | PHP |
| Database | MySQL |
| Frontend | Angular, HTML, CSS, TypeScript |
| Local tools | Visual Studio Code, XAMPP, Git; Node.js and npm for Angular |
| Version control and planning | GitHub repository, issues, and GitHub Projects |

## Planned architecture

The Angular interface will request lesson data and submit activity results to a PHP API. PHP will validate requests and use prepared database statements to read or save MySQL data. Lesson content, activity logic, progress storage, and UI components will be kept separate.

Planned implementation folders, to be added when development begins:

- `backend/` — PHP API, configuration examples, and backend tests.
- `database/` — schema and sample lesson data.
- `frontend/` — Angular application and frontend tests.
- `docs/` — planning, design references, review notes, and verification evidence.

## Project planning

Create a GitHub Project named **PixelPath Junior Capstone** and use the board columns **Todo**, **In Progress**, **Review**, and **Done**.

Course checkpoints:

| Course day | Deliverable |
| --- | --- |
| Day 5 | Submit the one-page proposal for instructor approval |
| Day 10 | Repository, README, Project board, and local environment |
| Days 15–75 | Build and verify the prototype; keep tasks current |
| Day 40 | First instructor code review |
| Day 60 | Second instructor code review |
| Before Day 80 | Submit a 3–5 minute demonstration video through Teams |
| Day 80 | Final demonstration, questions, and code review |

Course days are relative checkpoints, not calendar dates. Confirm actual appointment dates with the instructor.

## Testing plan

Verify the four activities with correct and incorrect inputs, mouse and touch controls, physical and on-screen keyboard input, and clear retry feedback. Verify progress persists after refresh and remains separate between demonstration profiles. Check the adult progress view, spoken instructions, mobile layouts, keyboard navigation, API input validation, and database failure handling. Record steps, expected results, actual results, and fixes in `docs/TESTING.md` when testing begins.

## Documentation and AI reflection

Update this README as development progresses. Keep instructor review notes and evidence of fixes. Complete [AIReflection.md](AIReflection.md) using the instructor's exact three questions and your own account of AI use, verification, and learning. The supplied file is a template and is not a finished reflection.

## Version control

Make small, descriptive commits tied to tasks, such as `Add computer parts lesson API` or `Fix touch dragging on activity screen`. Move tasks into Review when the checklist and verification are complete, then Done after review. Preserve a record of the Day 40 and Day 60 feedback and related changes.
