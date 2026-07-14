# Contributing to OpenSpin

Thanks for being here. OpenSpin runs on small, part-time contributions from people who care about open, reproducible spin-qubit tooling. There's no minimum commitment and no gatekeeping — if you have an hour and some interest, there's something useful you can do.

This guide covers the practical "how." For what we're about — the projects, the manifesto, the people — see the [org profile](https://github.com/OpenSpin/.github) or [openspin.github.io](https://openspin.github.io).

## Before you start

1. **Say hi in [Discussions](https://github.com/orgs/OpenSpin/discussions/1).** A one-line intro helps us point you at the right thing and avoid duplicated effort.
2. **Find or claim an issue.** The [roadmap board](https://github.com/OpenSpin/roadmap/issues) is where cross-project work and bounties are gathered; you can also browse [every open issue in the org](https://github.com/issues?q=org%3AOpenSpin+is%3Aissue+is%3Aopen). Comment "taking this" on the issue before you start so two people don't do the same work.
3. **No issue for what you want to do?** Open one. Describe the change or idea in a few sentences — it doesn't need to be formal.

## Where things live

Each simulator or tool lives in its own repo. Nothing is a monolith — pick the one that matches what you want to work on.

**Active**

- [ReadSpyn](https://github.com/OpenSpin/ReadSpyn) — readout simulator: spin-qubit readout traces for developing and benchmarking readout methods.
- [QDarts](https://github.com/qplai/QDarts) — charge stability diagram simulator for quantum dot arrays.
- [SpinSkills](https://github.com/OpenSpin/SpinSkills) — reusable, composable agent skills for spin-qubit workflows.
- [ChargeTwin](https://github.com/OpenSpin/ChargeTwin) — fast world/surrogate simulator of charge-noise disorder and dynamics.
- [SpinStoq](https://github.com/OpenSpin/SpinStoq) — generator of stochastic spatiotemporal noise trajectories.
- [SpinDeck](https://github.com/OpenSpin/SpinDeck) — map of open-source hardware relevant to spin qubits.

**Cooking**

- [SpinLib](https://github.com/OpenSpin/SpinLib) — structured library and database of spin-qubit papers.
- Tuning transformer — ML approach to automating quantum-dot tuning; still taking shape in [Discussions](https://github.com/orgs/OpenSpin/discussions).

**Planning** — the best moment to shape something

- [SpinFEM](https://github.com/OpenSpin/SpinFEM) — finite-element simulator of the Poisson equation from device geometry.

**Everything else**

- [SpinAcademy](https://github.com/OpenSpin/SpinAcademy) — reviews, courses, and starter resources. New to the field? Start here, no pressure to contribute immediately.
- [roadmap](https://github.com/OpenSpin/roadmap) — cross-project issues, visions, and the bounty board.
- [Wiki](https://github.com/OpenSpin/.github/wiki) — docs, meeting notes, design docs.
- [Discussions](https://github.com/orgs/OpenSpin/discussions) — questions, coordination, saying hi.

## The contribution avenues

In rough order of how much we need them:

1. **Cleaning & refactoring code** _(most valuable, lowest barrier)_ — improve readability, add docstrings, remove dead code, add tests, fix typing, tidy dependencies. You don't need deep domain knowledge to make a repo more usable for the next person. Most of the [roadmap board](https://github.com/OpenSpin/roadmap/issues) is this.
2. **Open-source simulators** — extend or improve [ReadSpyn](https://github.com/OpenSpin/ReadSpyn) (readout), [QDarts](https://github.com/qplai/QDarts) (charge stability diagrams), [ChargeTwin](https://github.com/OpenSpin/ChargeTwin) or [SpinStoq](https://github.com/OpenSpin/SpinStoq) (noise), or help start [SpinFEM](https://github.com/OpenSpin/SpinFEM) and the tuning transformer.
3. **New skills** — reusable analysis/automation pieces in [SpinSkills](https://github.com/OpenSpin/SpinSkills).
4. **Datasets & maps** — contribute or clean data in [SpinDeck](https://github.com/OpenSpin/SpinDeck) and [SpinLib](https://github.com/OpenSpin/SpinLib).
5. **Something we haven't thought of** — [propose an avenue](https://github.com/OpenSpin/roadmap/issues/new). Describe what you want to try, find a collaborator, and go.

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
