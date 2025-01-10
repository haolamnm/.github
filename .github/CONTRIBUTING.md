# Introduction

### Welcome to The Contributing Guides!

First off, thanks for taking the time to contribute! :tada: It’s people like you that make my project better. If you’re unsure about anything, just ask -- or submit the issue or pull request anyway. The worst that can happen is that you’ll be politely asked to change something. I appreciate any sort of contribution, and I don’t want a wall of rules to get in the way of that.

### Why you should read these Guidelines?

By following these guidelines, you help ensure that your contributions are effectively integrated into the project. I respect the time and effort you put into contributing, and by respecting these guidelines, you help maintain a collaborative and efficient workflow. In return, I will do my best to address your issues, assess your changes, and assist you in finalizing your pull requests.

### What we're looking for?

I welcome contributions of all kinds! Whether you're a seasoned developer or just starting out, your contributions help make this project better for everyone. Here are some ways you can get involved:

- Bug Reports and Feature Requests: Found a bug or have an idea for a new feature? Let me know by opening an issue.

Code Contributions: Help fix bugs, add new features, or improve the performance of the project. I'll help guide you through the process

- Documentation Improvements: Spotted a typo in the docs? Think you can explain something better? Then submit a pull request with your fix.

- Tests: Help me ensure reliability by adding or improving test cases.

- Discussions: Engage with the community by participating in issue discussions or brainstorming ideas for new features.

- Tutorials and Blog Posts: Share your knowledge by writing tutorials or blog posts that showcase how to use the project effectively.

### Contributions that I'm NOT looking for.

To save us both time, here are some types of contributions I am not looking for:

- Unsolicted Refactorings: While I appreciate your enthusiasm, major rewrites or reorganizations of the codebase may not align with the project's direction.

- Unclear or incomplete submissions: Submissions without enough context, clear descriptions, or actionable details are hard to review and may be closed.

# Ground Rules

To ensure a positive and productive experience for everyone, here are some guidelines and expectations:

### Expectations for behavior.

- Be respectful and considerate: Treat everyone with kindness, whether you're discussing code, suggesting improvements, or providing feedback.

- Keep communication clear: If you're reporting an issue or submitting a pull request, provide enough context to make it easy to understand and review.

- Be welcoming: Encourage and support new contributors, regardless of their background or experience level.

### Technical responsibilities.

- Test your changes: Make sure your contributions work as expected and don’t break existing functionality.

- Follow project conventions: Keep the codebase clean and consistent by adhering to the project's existing style and practices.

- Discuss major changes: Open an issue to propose and discuss big changes before implementing them. Transparency and collaboration make the project better.

- Keep it simple: Avoid over-engineering. Don’t add new classes or dependencies unless they’re absolutely necessary.

### Other notes

- Cross-platform compatibility: If your changes affect functionality, ensure they work across Windows, macOS, and Linux.

- Incremental improvements: Aim to make small, manageable contributions. One focused improvement per pull request is ideal.

# Your First Contribution

If this is your first time contributing to this project (or to open source in general), welcome! I’m excited to have you here. Here’s how you can get started:

### Where to start?

- **Beginner-friendly issues**: Look for issues labeled `good first issue`. These are designed to be approachable, typically requiring only a few lines of code or minor changes.

- **Help wanted**: Issues with the `help wanted` label are slightly more involved but still great for new contributors looking for a bit of a challenge.

You can find these issues by browsing the [issue list]().

### Resources for first-timers

If you're new to contributing to open source, here are some resources to guide you:

- [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github): A free video series that covers the basics of contributing to open source projects on GitHub.

- [First Timers Only](http://www.firsttimersonly.com/): A friendly community that helps new contributors make their first pull request.

- [Make a Pull Request](http://makeapullrequest.com/): A website that guides you through the process of making your first contribution.

# Getting started

I’m thrilled that you’re considering contributing to this project! Here’s a step-by-step guide to help you submit your first contribution:

### Small fixes and Obvious changes

For minor contributions, like fixing typos, updating documentation, or making formatting changes:

1. Fork the repository.
2. Make your changes.
3. Submit a pull request (PR). Be sure to include a clear description of the change.

No additional steps like signing agreements are required for these contributions.

### Larger contributions

If your contribution involves new functionality, bug fixes, or anything beyond a small change:

1. Create an issue: Open an issue to discuss your idea or bug fix. This ensures that the change aligns with the project’s goals before you start working on it.
2. Fork the repository: Clone it to your local environment.
3. Work on your changes:
  - Follow the project’s code style and conventions.
  - Write tests if your change impacts functionality.
4. Run the tests: Make sure all tests pass before submitting your PR.
5. Submit a pull request:
  - Include a clear description of your changes.
  - Reference the issue you created in step 1.
  - Follow the PR template, if one exists.
  - Notes on testing or known limitations of your changes.

Contributor License Agreement (CLA): If a CLA is required for this project, you’ll be prompted to sign it when submitting your PR. If you’re unsure, feel free to ask in the issue thread.

Code of Conduct: Please ensure your contributions adhere to the Code of Conduct.

By following this process, you help keep the project running smoothly and make it easier for everyone involved. Thank you for your contribution! 🎉

# How to report a bug?
### Security disclosures!

If you find a security vulnerability, do NOT open an issue. Instead, email me at [haolamnm.work@gmail.com](mailto:haolamnm.work@gmail.com). I’ll look into it as soon as possible and keep you informed of the steps we’re taking to address the issue.

To determine whether you're dealing with a security issue, ask yourself:
- Can I access something I shouldn’t have access to?
- Can I disable something for other people?

If the answer to either of these questions is "yes," please report it as a security issue. Even if you’re unsure, it’s better to err on the side of caution and email me directly.

### How to file a bug report?

When reporting a bug, you can use the following [bug report template](./ISSUE_TEMPLATE/bug_report.yml) to provide the necessary information. All the necessary information is included in the template, so you can just copy-paste it into the issue description.

# How to suggest a feature or enhancement?

### Project direction

Before suggesting a feature, please consider the project’s goals and direction. If you’re unsure, you can open an issue to discuss your idea and gather feedback.

- The goal of this project is to [briefly describe your goals or philosophy, e.g., "create lightweight, modular tools for X purpose."]

- Features should align with [specific guidelines or focus areas, e.g., "simplicity, maintainability, and cross-platform compatibility."]

This ensures that any new feature or enhancement contributes meaningfully to the project and benefits the community.

### Submitting a feature request

To suggest a feature or enhancement, please follow these steps

1. **Check existing requests**: Before submitting a new idea, take a look at the feature requests list to ensure it hasn’t already been suggested.
2. **Open a discussion**: If the idea is complex or requires community input, consider starting a discussion in the issues section to gauge interest and get feedback.
3. **Submit a feature request**: Submit a request using the [feature request template](./ISSUE_TEMPLATE/feature_request.yml). Include a clear description of the proposed feature and why it would be valuable.

Once submitted, I will review the suggestion and may ask for further clarification. For larger features, there may be some back-and-forth discussion to refine the idea.

Thank you for helping improve this project -- I appreciate your contribution!

# Code review process

### What to expect?

Since I manage this project independently, the code review process is straightforward:

1. Initial review: Once you submit a pull request (PR), I’ll review it personally. I aim to review contributions within [X days, e.g., 3-5 days] of submission.
2. Feedback and revisions:
  - If the PR requires changes, I’ll leave comments directly on the code or in the PR discussion.
  - You’re encouraged to address feedback and push updates to the same branch.
3. Acceptance or follow-up:
  - Once the changes meet the project’s standards, I’ll merge the PR.
  - If the PR doesn’t align with the project’s goals or remains inactive for more than [X weeks, e.g., 2 weeks], I may close it with a note explaining the decision.

### Commit access.

At the moment, I don’t grant direct commit access to contributors. If you’re a regular contributor and have consistently made valuable contributions, I may consider adding you as a collaborator in the future.

Thank you for your patience and understanding as I balance reviewing contributions alongside managing the project!

# The End

Thank you for taking the time to read these guidelines. I appreciate your interest in contributing to this project and look forward to your suggestions, bug reports, and code contributions. Your involvement helps make this project better for everyone, and I’m grateful for your support.

This document is inspired by the [CONTRIBUTING.md template](https://github.com/nayafia/contributing-template) by [Nadia](https://github.com/nayafia) and [Contributor Covenant](https://www.contributor-covenant.org/). If you have suggestions to improve these guidelines, please feel free to open an issue or submit a pull request.
