# Anastasiia Shakhovnina - Senior Test Engineer

My production work lives in my employers' private repositories, so I keep this repo as a demonstration of the code I can write. Over the years, I've accumulated some take-home assignments from job applications, along with a pet project I host for myself and my friends.

### 🏠 Household Tracker — my own product

[Live app](https://household-manager.duckdns.org/) · [Source](https://github.com/ansh120022/household_tracker)

A shared shopping and chores list for people who live together: items  running low appear on the shopping list, and recurring chores show up when they're due. The app designed to work without an account and doesn't require personal data.

- **Backend:** Python, FastAPI and SQLite
- **Frontend:** vibecoded - plain HTML, CSS and JavaScript
- **Ops:** runs on my own Linux server

I own it end to end, from requirements to deployment, and I have a few more features in mind.

### 🤖 Test automation samples

| Repo | What it shows |
| --- | --- |
| [test_framework_example](https://github.com/ansh120022/test_framework_example) | My most recent sample showing how I would build a test automation framework from scratch today, shown on the GitHub Gists API and UI. Playwright and TypeScript, with response validation in Zod, per-user session fixtures for permission tests, automatic cleanup of test data, a test data builder and page objects. |

#### 🐣 Some earlier work:

| Repo | What it shows |
| --- | --- |
| [test_task_for_chunky_bird](https://github.com/ansh120022/test_task_for_chunky_bird) | UI tests with Playwright and TypeScript, API tests with Vitest, schema validation with Zod, test data from Faker. Runs in GitHub Actions with parallel jobs and publishes an Allure report. |
| [api_tests_golang](https://github.com/ansh120022/api_tests_golang) | REST API tests in Go with httpexpect and JSON Schema validation |
| [pw-python](https://github.com/ansh120022/pw-python) | Playwright and pytest with the page object model. Runs in Docker. |
| [pw-ts](https://github.com/ansh120022/pw-ts) | Playwright with TypeScript, containerised |

### 🌍 Open source

I've always wanted to contribute to a meaningful open-source project, but it wasn't easy to find one where I could make a difference with my testing experience. My most recent attempt:

- **[CVAT](https://github.com/cvat-ai/cvat)** (computer vision annotation tool): I reported UX bugs and
  submitted fixes for them.
  - [#10969](https://github.com/cvat-ai/cvat/pull/10969) (merged): help links in the task form
    now open in a new tab, so in-progress form data isn't lost
  - [#10977](https://github.com/cvat-ai/cvat/pull/10977): test coverage for ground-truth
    validation, plus a fix for the quantity input helper

### 🎓 Mentoring

[buggy_app](https://github.com/ansh120022/buggy_app) I built it so my QA mentees could practise exploratory testing and bug reporting

---

💼 [My LinkedIn](https://www.linkedin.com/in/anastasia-shakhovnina/)
