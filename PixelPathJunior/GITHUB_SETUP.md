# GitHub setup guide

## 1 Create the GitHub Project

1. Open your GitHub profile, select **Projects**, then **New project**.
2. Under Start from scratch, select **Board**.
3. Name it **PixelPath Junior Capstone** and create it.
4. In the Project settings, set its description to **Plan and track the PHP/MySQL backend, Angular learning activities, testing, reviews, and submission for PixelPath Junior.**
5. Paste the following into the Project README and save:

> PixelPath Junior helps Grade 1 children practise foundational computer skills. This board tracks the proposal, setup, PHP/MySQL backend, Angular activities, progress features, testing, instructor reviews, AI reflection, and demonstration video. Move tasks through Todo, In Progress, Review, and Done. Course checkpoints are Day 10 setup, Day 40 and Day 60 reviews, video before Day 80, and Day 80 final submission.

6. Configure the Status field to contain **Todo**, **In Progress**, **Review**, and **Done**. Retain the default statuses and add Review if needed.
7. Keep the Board grouped by Status. Add a Table view named **Task List**.
8. In the Table view, create fields **Stage** (single select), **Priority** (single select), and **Target Day** (number).
9. Use Stage options Planning, Backend, Frontend, Review, Testing, Submission, and Priority options High, Medium, Low. Save view changes.
10. Set Project visibility so your instructor can access it. If private, invite their actual GitHub account with the access needed to review it.

## 2 Link the Project to the repository

Open the repository **Projects** tab, choose **Link a project**, search for **PixelPath Junior Capstone**, and select it. Link access is separate from permission to see a private Project. Add the actual Project URL to README.md after creating it.

## 3 Create and add initial tasks

1. Open docs/INITIAL_TASKS.md. It contains 23 titles, target course days, priorities, and completion checklists.
2. In your repository, select **Issues → New issue**. Use the provided Capstone task template, or create a blank issue.
3. Copy one title and its checklist. Assign yourself and select the capstone Project in the issue sidebar. Submit the issue.
4. Repeat for the other tasks. Alternatively, add each created issue URL in the Project Add item field.
5. In the Project Table view set Status = Todo and fill Stage, Priority, and Target Day using the overview table.
6. Start with the proposal approval, repository setup, and environment tasks. Mark only genuinely completed tasks Done.

A Markdown task list does not automatically populate GitHub Projects. Creating issues and adding them to the Project is required. Draft Project items are a quicker alternative, but repository issues provide a better record of discussion, commits, and review.

Optional workflows: configure Auto-add to project for this repository with filter `is:issue`; set newly added items to Todo; set closed issues to Done. Check that the workflow is enabled. Auto-add covers matching new items; manually add existing issues if needed.

## 4 Clone and work locally

After the online repository exists and starter files are committed:

```bash
git clone https://github.com/MovingSpots/PixelPathJunior.git
cd PixelPathJunior
code .
```

Replace MovingSpots if your current account is different. Open the folder in VS Code using File → Open Folder if the code command is unavailable.

To include any starter files omitted by the web upload, copy them into this clone, including .gitignore and .github, then:

```bash
git status
git add .
git commit -m "Add repository setup files"
git push origin main
```

For later changes, use the same add, commit, and push flow with a message describing the actual change. If there are no changes, do not create an empty commit. Pull with `git pull --ff-only` before starting work on a clone that another computer has updated.

## 5 Configure your development tools

- Use VS Code and Git for project work.
- Start Apache and MySQL in XAMPP and verify the local server works.
- During database development, create the project database from a committed schema using fictional seed data.
- Prepare Node.js and npm when beginning Angular. Record the versions you actually use.
- Keep backend and frontend source in this repository once created. Commit config examples rather than real credentials.
- Replace the README's planning-only run section with tested instructions when the app becomes runnable.

## 6 Verify the setup

- README shows the app name, introduction, proposed features, technology, and course checkpoints.
- AIReflection.md exists and is visibly marked unfinished.
- Project is linked and shows all 23 tasks in appropriate status columns.
- Project fields display Stage, Priority, and Target Day.
- Local clone opens correctly; Git status shows the expected files.
- Instructor can access both the repository and the Project.

## Official GitHub references

- https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
- https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project
- https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/adding-your-project-to-a-repository
- https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project
- https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects
