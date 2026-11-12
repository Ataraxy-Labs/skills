# Ataraxy Labs skills

Agent skills from [Ataraxy Labs](https://ataraxy-labs.com).

## land

[land](https://useland.dev) merges your agents' finished branches, runs only the tests that read the functions that changed on the merged result, and tells the agent which branches landed and which broke tests, with the failing test, the culprit and a one-command repro.

Install the skill into Claude Code, Codex, Cursor and other agents:

```sh
npx skills add Ataraxy-Labs/skills --skill land
```

Then install the land CLI and sign in:

```sh
curl -fsSL https://useland.dev/install | sh
```

The skill itself is in [skills/land/SKILL.md](skills/land/SKILL.md). How land works is at [useland.dev/how-it-works](https://useland.dev/how-it-works).
