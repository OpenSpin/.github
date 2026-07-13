# Contributing to OpenSpin

Thanks for being here. OpenSpin runs on small, part-time contributions from people who care about open, reproducible spin-qubit tooling. There's no minimum commitment and no gatekeeping — if you have an hour and some interest, there's something useful you can do.

This guide covers the practical "how." For what we're about, see the [org profile](https://github.com/OpenSpin/.github).

## Before you start

1. **Say hi in [Discussions](https://github.com/orgs/OpenSpin/discussions/4).** A one-line intro helps us point you at the right thing and avoid duplicated effort.
2. **Find or claim an issue.** Browse [good first issues](https://github.com/OpenSpin/.github/labels/good%20first%20issue) across the repos. Comment "taking this" on the issue before you start so two people don't do the same work.
3. **No issue for what you want to do?** Open one. Describe the change or idea in a few sentences — it doesn't need to be formal.

## Where things live

- **Simulators & tools** — each lives in its own repo: [ReadSpyn](https://github.com/OpenSpin/ReadSpyn), [QDarts](https://github.com/qplai/QDarts), [SpinSkills](https://github.com/OpenSpin/SpinSkills), [Spin-Deck](https://github.com/OpenSpin/spin-deck).
- **Docs, meeting notes, design docs** — the [Wiki](https://github.com/OpenSpin/.github/wiki).
- **Discussion, questions, coordination** — [Discussions](https://github.com/orgs/OpenSpin/discussions).

## The contribution avenues

In rough order of how much we need them:

1. **Cleaning & refactoring code** _(most valuable, lowest barrier)_ — improve readability, add docstrings, remove dead code, add tests, fix typing, tidy dependencies. You don't need deep domain knowledge to make a repo more usable for the next person.
2. **Open-source simulators** — extend or improve [ReadSpyn](https://github.com/OpenSpin/ReadSpyn) (readout), [QDarts](https://github.com/qplai/QDarts) (charge stability diagrams), or help start the tuning transformer.
3. **New skills** — reusable analysis/automation pieces in [SpinSkills](https://github.com/OpenSpin/SpinSkills).
4. **Datasets** — contribute or clean data in [Spin-Deck](https://github.com/OpenSpin/spin-deck).

## Making a change

1. **Fork** the relevant repo and create a branch: `git checkout -b clean/readspyn-docstrings`.
2. **Keep it small.** One focused change per PR. Small PRs get reviewed and merged; large ones stall.
3. **Match the repo.** Follow the existing style and structure. If a repo has its own linter/formatter config, run it before committing.
4. **Write a clear PR description.** Link the issue (`Closes #12`), say what changed and why. Screenshots or before/after are great for anything visual.
5. **Open the PR** against `main`. A maintainer or another contributor will review. Expect friendly, low-ceremony feedback.

### Commit & PR conventions

- Descriptive commit messages in the imperative ("Add docstrings to readout sampler").
- One logical change per commit where practical.
- Draft PRs are welcome if you want early feedback.

## If you can't finish something

Life happens. If you claimed an issue and can't complete it, just leave a comment saying so and roughly where you got to. That frees it up for the next person — no hard feelings, this is how a part-time collective is supposed to work.

## Ground rules

- **Be kind and patient.** Most of us are doing this on the side.
- **Assume good faith.** Ask questions freely; nobody is expected to know everything.
- **Prefer small PRs over big ones.**
- **Leave breadcrumbs.** Notes on issues and PRs are what let the next contributor pick up where you left off.

## Questions?

Open a thread in [Discussions](https://github.com/orgs/OpenSpin/discussions) — no question is too basic.
