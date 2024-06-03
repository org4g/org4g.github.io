---
createdAt: "2024-06-03T08:03:00.000Z"
updatedAt: "2024-06-03T08:03:00.000Z"
Tags:
  - "Codebase"
title: "Code Reviews"
---

> 💡 This template documents how to review code. Helpful for new and remote employees to get and stay aligned.

# Philosophy

Why do you perform code reviews? What are your guiding principles for these reviews?

You may want to mention other pages here. Like Engineering Guidelines. To link to another page inline, type `@` followed by the name of the page: [Engineering Guidelines](https://www.notion.so/a7c774830d1b43f7a8c8f3cf1c6f8937)

# Preparing Code for Review

Preparation sets your reviewers up for success.

### Commit Messages

Make sure your commit messages are descriptive.

### Github PR Descriptions

Your PR descriptions should be an extension of your commit messages. Write about both what the commit changes, and how you implemented the change.

# Performing Code Reviews

### How to Review

- Make two passes over the PR if it's substantial.
  - On the first pass, come to an understanding of the code change at a high level.
  - On the second pass, pay more attention to semantic details.

# Examples

```javascript
var commentCount = 0;
```

You might suggest that this be a `let` instead of `var`.
