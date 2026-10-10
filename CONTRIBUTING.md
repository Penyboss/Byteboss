# Contributing to Byteboss

Byteboss is currently a documentation-only scaffold for a PixelVox FAQ bot.
Read the [project overview](README.md) before proposing a change. There is no
application, supported runtime, or test command in this repository yet.

## Choose a focused contribution

Useful contributions at this stage include:

- Correcting unclear or inaccurate documentation.
- Proposing an FAQ entry with a verifiable source.
- Explaining a concrete use case that helps answer an open implementation
  question in the README.

Search the [existing issues](https://github.com/Penyboss/Byteboss/issues) and
[pull requests](https://github.com/Penyboss/Byteboss/pulls) before opening a new
discussion. For a substantial implementation proposal, describe the intended
behavior and trade-offs first so the platform and scope can be discussed.

## Propose an FAQ entry

Use the following outline in an issue or pull request. It is a proposal format,
not a bot configuration file or an implemented data schema.

- **Question:** A specific question a PixelVox user would ask.
- **Proposed answer:** A short answer in plain language.
- **Source:** A public, authoritative link that supports the answer.
- **Checked on:** The date you verified the source, in `YYYY-MM-DD` format.
- **Scope:** Any relevant product version, plan, platform, or other limitation.
- **Uncertainty:** Missing information or details that still need confirmation.

If a source is unavailable or contradictory, record the uncertainty rather than
presenting a guess as a confirmed answer. Do not copy private conversations,
account details, access tokens, or other confidential information into a public
issue or pull request.

## Explain a documentation problem

Include the affected file or section, what is confusing or incorrect, and the
proposed correction. Link the evidence for factual changes. When discussing
future behavior, label it as a proposal rather than an existing feature.

## Submit a pull request

1. Create a branch for one coherent change, or use a fork if you do not have
   write access.
2. Make the change and check the final diff for unrelated edits.
3. Open a pull request against `main`. Use a draft if work or validation remains.
4. Summarize the problem, the change, and how you checked it. Link an issue when
   one already exists and is relevant; a small documentation correction does
   not need a separate issue.
5. Address feedback and keep the documentation consistent with the repository's
   actual state.

## Check documentation before review

- Preview the Markdown and check headings, lists, and code formatting.
- Confirm relative links point to files or headings that exist.
- Open source links and check that they support the surrounding claims.
- Keep proposed features distinct from implemented behavior.
- Remove secrets, personal data, unsupported claims, and unrelated changes.
- State what you checked and any remaining uncertainty in the pull request.

There are currently no automated tests or lint commands to run. A documentation
review is not evidence that a bot works. If an implementation is added later,
its contribution instructions should include the real setup and test commands.
