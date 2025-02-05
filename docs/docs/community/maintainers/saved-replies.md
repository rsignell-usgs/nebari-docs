---
title: Saved replies
description: Standard replies for interacting with contributors
id: saved-replies
---

## Standard replies

It may be helpful to store some of these in [GitHub’s saved replies](https://github.com/settings/replies/) for faster access.

### Issue triaging

- **Usage question**

  *action: redirect to support channels and close the issue*

  ```md
  Thanks for taking the time to open an issue!

  You are asking a usage question. The issue tracker is for bugs and new features.
  I'm going to close this issue, but feel free to visit our support resources:

  - [User documentation](https://nebari.dev/docs/welcome)
  - [Troubleshooting guide](https://nebari.dev/docs/troubleshooting)
  - [User forum](https://github.com/orgs/nebari-dev/discussions)
  ```

- **Self-contained example for bug**

  *action: add `needs: investigation 🔍` label*

  ```md
  Thanks for reporting this and helping make Nebari better!

  Please provide a [self-contained example code](https://stackoverflow.com/help/mcve), including imports and data (if possible),
  so that other contributors can run it and reproduce your issue.
  Ideally your example code should be minimal.
  ```

- **Duplicate issue**

  *action: add `type: duplicate 👯‍♀️` label and link to duplicate issue*

  ```md
  Thanks for taking the time to contribute!

  We noticed that this is a duplicate of [Issue URL]. You may want to subscribe there for updates.

  Because we treat our issues list as the project team's backlog, we close duplicates to focus our work and not have to touch the same chunk of code for the same reason multiple times. This is also why we may mark something as duplicate that isn't an exact duplicate but is closely related.
  ```

- **No response: closing issue**

    *action: add `status: abandoned 🗑` label and close the issue*

    ```md
    Thanks for taking the time to open an issue!

    Unfortunately, we haven't heard back from you in a while, so we're going to close this issue.
    With only the information that is currently in the issue, we don't have enough information to take action. I'm going to close this but don't hesitate to reach out if you have or find the answers we need, we'll be happy to reopen the issue.
    ```

- **You are welcome to update the docs**

  ```md
  Thanks for taking some time to make our documentation better!

  Please feel free to offer a pull request updating the documentation if you feel it could be improved.
  You can find our contribution guidelines in the [Nebari documentation](https://nebari.dev/community)
  ```

### Better comments or issues

- **Linking to code**

    ```md
    For clarity's sake, you can link to code like [this](https://help.github.com/articles/creating-a-permanent-link-to-a-code-snippet/).
    ```

- **Linking to comments**

  ```md
  Please use links to comments, which make it a lot easier to see what you are referring to, rather than linking to the issue.
  See [this StackOverflow question](https://stackoverflow.com/questions/25163598/how-do-i-reference-a-specific-issue-comment-on-github) for more details.
  ```

- **Code blocks**

  ```md
  Readability can be greatly improved if you [format](https://help.github.com/articles/creating-and-highlighting-code-blocks/)
  your code snippets and complete error messages appropriately.
  You can edit your issue descriptions and comments at any time to improve readability.
  This helps maintainers a lot. Thanks!
  ```

### Contribution reviews

- **PR-WIP: What is needed before merge?**

  ```md
  Please clarify (perhaps as a TODO list in the PR description) what work you believe still needs to be done before it can be reviewed for merge.
  When it is ready, please remove the WIP from the title and request a review from a maintainer.
  ```

- **PR: Needs tests**

  *action*: add `needs: tests ✅` label

  ```md
  Thanks for your submission!

  We require automated tests for all pull requests that include new or changed code. We do this so that we can ensure that we don't accidentally break your shiny new code the next time we or some other contributor submits a change. If you need help writing automated tests, check out {{the community forum and/or documentation}}. There are a bunch of helpful community members that should be willing to point you in the right direction.
  ```

- **Fix tests**

  *action*: add `needs: changes 🧱` label

  ```md
  We notice that the automated tests are failing on this pull request. In our investigation it appears that the failing tests are caused by your changes.
  In order for this pull request to be accepted, the tests will have to be fixeed.
  ```

### Code of conduct

:::note
The following replies should only be used by [Nebari's Code of Conduct committee members][nebari-coc-committee].
:::

- **First warning**

  ```md
  [[at-mention]] your comment was [[minimized|deleted]] as a violation of the [Nebari Code of Conduct](https://github.com/nebari-dev/governance/blob/main/CODE_OF_CONDUCT.md). You may consider this an official warning.

  Please do not interact with the project for 24 hours.
  After that, please look through your open issues and edit them to ensure they're entirely on-topic,
  and we can continue the discussion here about the best way to go forward.
  ```

<!-- Links -->
[nebari-coc-committee]: https://github.com/nebari-dev/governance/blob/main/code-of-conduct/coc_enforcement.md#the-code-of-conduct-committee
