# Contributing to OSGeo Suomi projects

Thank you for your interest in contributing to a project under the
[OSGeo Suomi ry](https://www.osgeo.fi/) GitHub organization. These guidelines
apply to every repository under [github.com/osgeosuomi](https://github.com/osgeosuomi)
unless an individual repository overrides them with its own `CONTRIBUTING.md`.


## Ways to contribute

- **Report bugs and request features** by opening an issue in the relevant
  repository. If you are unsure which repository, open an issue in
  [osgeosuomi/.github](https://github.com/osgeosuomi/.github/issues).
- **Improve documentation.** Typo fixes, clarifications, and translations are
  always welcome.
- **Submit code** via a pull request (see below).
- **Help review pull requests.** Thoughtful review is one of the most valuable
  contributions a community member can make.

## Pull request workflow

1. **Discuss first for non-trivial changes.** Open an issue describing the
   problem and your proposed approach before writing significant code. This
   saves everyone's time if the direction needs adjustment.
2. **Fork and branch.** Create a feature branch from the repository's default
   branch.
3. **Keep changes focused.** One logical change per pull request. Smaller PRs
   get reviewed faster and merged more reliably.
4. **Write a clear PR description.** Explain the motivation, the approach, and
   any trade-offs or open questions. The PR description should be written by a
   human — see the AI tool use policy below.
5. **Run the project's tests and linters locally** before requesting review,
   if the repository provides them. Note that GitHub Actions workflows on a
   first-time contributor's pull request will not run until a maintainer
   approves them — this is a GitHub default, not a problem with your PR.
6. **Respond to review.** Maintainers will review as time permits. Please
   address feedback promptly and ask questions if anything is unclear.


## AI tool use policy

OSGeo Suomi welcomes contributions crafted with the help of LLMs and other
AI-assisted tooling, **provided that there is a human in the loop**. This
policy is adapted from the
[QGIS AI tool use policy (QEP-408)](https://github.com/qgis/QGIS-Enhancement-Proposals/blob/master/qep-408-ai-tool-policy.md)
and the [LLVM AI Tool Policy](https://github.com/llvm/llvm-project/blob/main/llvm/docs/AIToolPolicy.md).

### The contributor is the author

You may use any tools you like to draft a contribution, but **you are the
author and you are fully accountable for the result**. Before you ask anyone
else to review your contribution, you must:

- Read and understand every line of code, documentation, or text you submit.
- Be able to answer review questions about your work without re-prompting a
  tool.
- Be confident the contribution meets the project's quality bar — submitting it
  is asking a maintainer to spend their limited time reviewing it.

If you are new to a project, **start with small contributions** that you can
fully understand. Learning happens through small steps, feedback, and
iteration. Forwarding maintainer feedback to an LLM does not help you grow and
does not sustain the community.

### Be transparent about tool use

If a substantial part of a contribution was generated with AI assistance,
disclose it. Either:

- Mention it in the pull request description, **or**
- Add a commit trailer such as `Assisted-by: <tool name>` (e.g.
  `Assisted-by: Claude Code`).

Transparency helps reviewers focus their attention and helps the community
build shared norms around these tools. The goal is **not** to track which
parts of the codebase are generated.

### Write your own PR descriptions

Pull request descriptions, design proposals, and issue reports should be
written by you. Using a tool for translation or copy-editing is fine; pasting
LLM output as your design rationale is not.

### No autonomous agents in our spaces

Tools or agents that post comments, open issues, or submit pull requests
**without a human reviewing each action first** are not permitted. An opt-in
assistant that keeps a human in the loop on every published action is fine.

### Copyright

You are responsible for ensuring you have the right to submit your
contribution under the project's license. Using an AI tool to reproduce
copyrighted material does not strip the copyright; contributions found to
contain such material will be removed.

## Extractive contributions

A contribution should be worth more to the project than the time it takes to
review it. Maintainer attention is the scarcest resource in any open source
project, and submitting unreviewed AI output shifts work from the contributor
to the reviewer.

If a maintainer judges a contribution to be **extractive** — too large, too
unfocused, or insufficiently understood by its author — they may ask for the
PR to be reduced in scope, request additional justification, or close it. The
best ways to make a contribution less extractive are to **reduce its size and
complexity** and to **increase its value to the community**.

Repeated violations of this policy may result in temporary or permanent
exclusion from the organization.

## Licensing

- Every repository must carry an OSI-approved license. See the
  [organization profile](./profile/README.md) for guidance.
- By submitting a pull request you agree that your contribution is licensed
  under the same license as the repository you are contributing to.
- Add or preserve copyright headers in source files where the project uses
  them.

## Questions

For questions about contributing, open an issue in
[osgeosuomi/.github](https://github.com/osgeosuomi/.github/issues) or email
**info at osgeo.fi**.
