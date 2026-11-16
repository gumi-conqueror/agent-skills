# Agent skills

Shared skill entry points with pinned upstream submodules. Use [the catalog](skills/README.md) to select a skill.

## Initialize submodules

```sh
git clone --recurse-submodules https://github.com/gumi-conqueror/agent-skills.git
```

For an existing checkout, run `git submodule update --init --recursive`.
To use the skills in a project, add this repository at `.agents`:

```sh
git submodule add https://github.com/gumi-conqueror/agent-skills.git .agents
git submodule update --init --recursive
```

Keep project rules in the project's root AGENTS.md. Do not edit pinned upstream content. Review an upstream change, check out the chosen commit, and commit the updated submodule reference here.

Entry points use MIT. Upstream submodules retain their own licenses.
