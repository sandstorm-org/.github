# AI Contribution Policy

Sandstorm is a complex project deployed across thousands of servers. It is a stable platform that numerous app projects are built on top of, and is considered a security product: We consider stability and security more important than development pace. Because of the complexity of the platform, it's key that we maintain a high standard of quality and maintainability, and only make changes with careful thought. We also have very limited resources as a community project: The burden of code review to land an improvement or feature can be significant.

## Accountability

AI assistance tools have the ability to augment developers' ability to write, test, and fix code more quickly, however, they are tools, not developers themselves. Whether or not you use AI tools, we expect contributions to be made by humans, and humans must take responsibility for that work.

**The human contributor is the sole party responsible for the contribution.**

If you submit a PR that includes AI-generated code, documentation, or comments:

- You must fully understand every line of code in the submission.
- You must be able to explain the "why" behind the implementation during the review process.

"The AI generated it and it works for me" is never an acceptable answer to a reviewer's question. Copy-and-pasting to and from an AI chatbot during the process of code review is not acceptable (unless this is only for translation to and from English). If a maintainer suspects you do not understand your PR, it will be closed immediately.

Autonomous AI agents should not submit PRs to our project, and should not be listed as a "co-author" to any commits. Please include a human-written description for your pull request, and if you feel that AI-generated information provides additional useful context, please indicate that clearly in the human-written portion of the PR, and include the additional information below.

## Disclosure

If AI was used to generate a significant portion of your contribution (i.e. beyond simple autocomplete), we require you to disclose it in the PR description.

Please add a trailer to your commit message in the following format:

```text
Assisted-by: Name of AI
```

Examples:

```text
Assisted-by: ChatGPT 5.2
Assisted-by: Claude Opus 4.5
Assisted-by: Google Gemini 3
```

## Copyright & Legal

By submitting a contribution to Sandstorm, you represent and warrant that:

1. You have the legal right to submit the contribution under the project's (or specific repository) licence.
2. The contribution does not violate the intellectual property rights of any third party.
3. If AI was used, the resulting code does not violate the terms of service of the AI provider and does not include "regurgitated" code from libraries with incompatible licences to the repository you’re submitting it to.

If you cannot guarantee the provenance and legal safety of the AI-generated code, **do not submit it**.

## Acknowledgement

This policy is heavily borrowed from the [Mastodon AI Policy](https://github.com/mastodon/.github/blob/main/AI_POLICY.md), which was in turn based on the CloudNativePG policy, which was inspired by the Ghostty AI Policy.
