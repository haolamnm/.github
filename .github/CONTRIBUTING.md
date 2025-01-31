# Contributing Guidelines

Welcome to the Contributing Guidelines! This document outlines the expectations for behavior, technical responsibilities, and other notes for contributing to the project.

## Table of Contents
- [Introduction](#introduction)
	- [Welcome to The Contributing Guides!](#welcome-to-the-contributing-guides)
	- [Why you should read these Guidelines?](#why-you-should-read-these-guidelines)
	- [What I'm looking for?](#what-im-looking-for)
	- [Contributions that I'm NOT looking for!](#contributions-that-im-not-looking-for)
- [Ground Rules](#ground-rules)
  - [Expectations for behavior](#expectations-for-behavior)
  - [Technical responsibilities](#technical-responsibilities)
  - [Other notes](#other-notes)
- [Your First Contribution](#your-first-contribution)
	- [Where to start?](#where-to-start)
	- [Resources for first-timers](#resources-for-first-timers)
- [Getting started](#getting-started)
	- [Small fixes and Obvious changes](#small-fixes-and-obvious-changes)
	- [Larger contributions](#larger-contributions)
	- [Other notes](#other-notes-1)
- [How to report a bug?](#how-to-report-a-bug)
	- [Security disclosures!](#security-disclosures)
	- [How to file a bug report?](#how-to-file-a-bug-report)
- [How to suggest a feature or enhancement?](#how-to-suggest-a-feature-or-enhancement)
	- [Project direction](#project-direction)
	- [Submitting a feature request](#submitting-a-feature-request)
- [Code review process](#code-review-process)
	- [What to expect?](#what-to-expect)
	- [Commit access](#commit-access)
- [The End](#the-end)

# Introduction

### Welcome to The Contributing Guides!

First off, thanks for taking the time to contribute! :tada: It’s people like you that make my project better. If you’re unsure about anything, just ask or submit the issue or pull request anyway. The worst that can happen is that you’ll be politely asked to change something. I appreciate any sort of contribution, and I don’t want a wall of rules to get in the way of that.

### Why you should read these Guidelines?

By following these guidelines, you help ensure that your contributions are effectively integrated into the project. I respect the time and effort you put into contributing, and by respecting these guidelines, you help maintain a collaborative and efficient workflow. In return, I will do my best to address your issues, assess your changes, and assist you in finalizing your pull requests.

### What I'm looking for?

I welcome contributions of all kinds! Whether you're a seasoned developer or just starting out, your contributions help make this project better for everyone. Here are some ways you can get involved:
- **Bug Reports and Feature Requests**: Found a bug or have an idea for a new feature? Let me know by opening an issue.
- **Code Contributions**: Help fix bugs, add new features, or improve the performance of the project. I'll help guide you through the process
- **Documentation Improvements**: Spotted a typo in the docs? Think you can explain something better? Then submit a pull request with your fix.
- **Tests**: Help me ensure reliability by adding or improving test cases.
- **Discussions**: Engage with the community by participating in issue discussions or brainstorming ideas for new features.
- **Tutorials and Blog Posts**: Share your knowledge by writing tutorials or blog posts that showcase how to use the project effectively.

### Contributions that I'm NOT looking for!

To save us both time, here are some types of contributions I am not looking for:
- **Unsolicted Refactorings**: While I appreciate your enthusiasm, major rewrites or reorganizations of the codebase may not align with the project's direction.
- **Unclear or incomplete submissions**: Submissions without enough context, clear descriptions, or actionable details are hard to review and may be closed.

# Ground Rules

### Expectations for behavior

- **Be respectful and considerate**: Treat everyone with kindness, whether you're discussing code, suggesting improvements, or providing feedback.
- **Keep communication clear**: If you're reporting an issue or submitting a pull request, provide enough context to make it easy to understand and review.
- **Be welcoming**: Encourage and support new contributors, regardless of their background or experience level.

### Technical responsibilities

- **Test your changes**: Make sure your contributions work as expected and don’t break existing functionality.
- **Follow project conventions**: Keep the codebase clean and consistent by adhering to the project's existing style and practices.
- **Discuss major changes**: Open an issue to propose and discuss big changes before implementing them. Transparency and collaboration make the project better.
- **Keep it simple**: Avoid over-engineering. Don’t add new classes or dependencies unless they’re absolutely necessary.

### Other notes

- **Cross-platform compatibility**: If your changes affect functionality, ensure they work across Windows, macOS, and Linux.
- **Incremental improvements**: Aim to make small, manageable contributions. One focused improvement per pull request is ideal.

# Your First Contribution

### Where to start?

If this is your first time contributing to this project (or to open source in general), welcome! I’m excited to have you here. Here’s how you can get started:

- **Beginner-friendly issues**: Look for issues labeled `good first issue`. These are designed to be approachable, typically requiring only a few lines of code or minor changes.
- **Help wanted**: Issues with the `help wanted` label are slightly more involved but still great for new contributors looking for a bit of a challenge.

You can find these issues by browsing the [issues list]().

### Resources for first-timers

If you're new to contributing to open source, here are some resources to guide you:

- [**How to Contribute to an Open Source Project on GitHub**](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github): A free video series that covers the basics of contributing to open source projects on GitHub.
- [**First Timers Only**](http://www.firsttimersonly.com/): A friendly community that helps new contributors make their first pull request.
- [**Make a Pull Request**](http://makeapullrequest.com/): A website that guides you through the process of making your first contribution.

# Getting started

### Small fixes and Obvious changes

For minor contributions, like fixing typos, updating documentation, or making formatting changes:
1. Fork the repository: Click the “Fork” button to create your copy.
2. Clone the repository: Clone the repo to your local machine and set it up according to the project’s README file.
3. Make your own changes.
4. Submit a pull request (PR). Don't worry, I have a [pull request template](./PULL_REQUEST_TEMPLATE.md) to help you include all the necessary information.

No additional steps like signing agreements are required for these contributions.

### Larger contributions

If your contribution involves new functionality, bug fixes, or anything beyond a small change:
1. **Create an issue**: Open an issue to discuss your idea or bug fix. This ensures that the change aligns with the project’s goals before you start working on it.
2. **Fork the repository**: Clone it to your local environment.
3. **Work on your changes**: Follow the project’s code style and conventions. Write tests if your change impacts functionality.
4. **Run the tests**: Make sure all tests pass before submitting your PR.
5. **Submit a pull request**: Include a clear description of your changes. Reference the issue you created in step 1. Follow the [PR template](./PULL_REQUEST_TEMPLATE.md) to provide all necessary details. Notes on testing or known limitations of your changes. This helps me understand your contribution and review it more effectively. That's it!

### Other notes

- **Contributor License Agreement (CLA)**: If a CLA is required for this project, you’ll be prompted to sign it when submitting your PR. If you’re unsure, feel free to ask in the issue thread.
- [**Code of Conduct**](./CODE_OF_CONDUCT.md): Please ensure your contributions adhere to the Code of Conduct.

By following this process, you help keep the project running smoothly and make it easier for everyone involved. Thank you for your contribution! 🎉

# How to report a bug?

### Security disclosures!

If you find a **security vulnerability**, do **NOT** open an issue. Instead, email me at [haolamnm.work@gmail.com](mailto:haolamnm.work@gmail.com). I’ll look into it as soon as possible and keep you informed of the steps we’re taking to address the issue.

To determine whether you're dealing with a security issue, ask yourself:
- Can I access something I shouldn’t have access to?
- Can I disable something for other people?

Make sure to include all the necessary information in your report. This includes the following details:
- Description of the vulnerability.
- Steps to reproduce the issue.
- Potential impact of the vulnerability.
- Any additional information that could help us understand and address the issue.
- If possible, include a fix or mitigation for the vulnerability.

In the email subject line, please use the following format: "[Security Issue] – Brief description of the issue". This will help us quickly identify and prioritize the report.

### How to file a bug report?

I've already set up the following [bug report template](./ISSUE_TEMPLATE/bug_report.yml) to help you provide the necessary information. What you need to do is just navigate to the **issues tab** and click on the "**New Issue**" button. Then, select the "Bug report" template and fill in the necessary information.

# How to suggest a feature or enhancement?

### Project direction

Before suggesting a feature, please consider the project’s goals and direction. If you’re unsure, you can open an issue to discuss your idea and gather feedback.
- The goal of this project is to [*briefly describe your goals*, e.g., "create lightweight, modular tools for X purpose."]
- Features should align with [*specific guidelines or focus areas*, e.g., "simplicity, maintainability, and cross-platform compatibility."]

This ensures that any new **feature** or **enhancement** contributes meaningfully to the project and benefits the community.

### Submitting a feature request

To suggest a feature or enhancement, please follow these steps:
1. **Check existing requests**: Before submitting a new idea, take a look at the feature requests list to ensure it hasn’t already been suggested.
2. **Open a discussion**: If the idea is complex or requires community input, consider starting a discussion in the issues section to gauge interest and get feedback.
3. **Submit a feature request**: I've created a [feature request template](./ISSUE_TEMPLATE/feature_request.yml) to help you provide the necessary information. Navigate to the **issues tab**, click on the "**New Issue**" button, select the "Feature request" template, and fill in the details.

Once submitted, I will review the suggestion and may ask for further clarification. For larger features, there may be some back-and-forth discussion to refine the idea. Your input is valuable, and I appreciate your help in shaping the project!

# Code review process

### What to expect?

Since I manage this project independently, the code review process is straightforward:
1. **Initial review**: Once you submit a pull request (PR), I’ll review it personally. I aim to review contributions within [X days, e.g., 3-5 days] of submission.
2. **Feedback and revisions**: If the PR requires changes, I’ll leave comments directly on the code or in the PR discussion. You’re encouraged to address feedback and push updates to the same branch.
3. **Acceptance or follow-up**: Once the changes meet the project’s standards, I’ll merge the PR. If the PR doesn’t align with the project’s goals or remains inactive for more than [X weeks, e.g., 2 weeks], I may close it with a note explaining the decision.

### Commit access

At the moment, I don’t grant direct commit access to contributors. If you’re a regular contributor and have consistently made valuable contributions, I may consider adding you as a collaborator in the future.

Thank you for your patience and understanding as I balance reviewing contributions alongside managing the project!

# The End

Thank you for taking the time to read these guidelines. I appreciate your interest in contributing to this project and look forward to your suggestions, bug reports, and code contributions. Your involvement helps make this project better for everyone, and I’m grateful for your support.

This document is inspired by the [CONTRIBUTING.md template](https://github.com/nayafia/contributing-template) by [Nadia](https://github.com/nayafia) and the [Contributor Covenant](https://www.contributor-covenant.org/). If you have suggestions to improve these guidelines, please feel free to open an issue or submit a pull request.
