# Gopioneers

Gopioneers is a software company founded by Son Tran. We build tools for developers who work alongside AI coding agents.

## oneshot-ai

> Assign issues to AI coding agents. Review the diff. Ship.

oneshot-ai is a self-hosted issue board for Claude Code. Every issue runs on its own git worktree and branch, so you can hand several tasks to agents at once and still review each change on its own.

**How it works**

1. Write an issue and assign it to an agent profile.
2. oneshot-ai creates a branch and a git worktree for the issue, then runs Claude Code inside it.
3. Follow the run live: reasoning, tool calls and test output stream to the board.
4. Review the diff. Merge it, open a pull request, or leave feedback and the agent continues in the same session.

**Highlights**

- **One issue, one worktree.** Agents never touch your working copy or each other's.
- **Feedback keeps context.** A comment resumes the same Claude Code session in the same worktree.
- **Usage you can see.** Cost, turns and tokens are recorded for every run.
- **Runs on your machine.** One Go binary and one SQLite file, bound to `127.0.0.1` by default.

**Status:** in development. We are building the MVP now.

[oneshotai.gopioneers.space](https://oneshotai.gopioneers.space)

## Get in touch

- Email: [oneshotai@gopioneers.space](mailto:oneshotai@gopioneers.space)
- Website: [oneshotai.gopioneers.space](https://oneshotai.gopioneers.space)
