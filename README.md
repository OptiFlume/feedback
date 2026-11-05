# OptiFlume feedback

Bug reports, feature requests and questions for [OptiFlume](https://optiflume.ai), the model router,
context manager and guardian for Cursor, Claude Code and Codex on macOS. OptiFlume's source is not
published; this repository is where its users and its team talk in public.

- **Report a bug or request a feature:** [New issue](https://github.com/optiflume/feedback/issues/new/choose)
- **Ask how something works:** [Discussions](https://github.com/optiflume/feedback/discussions), after the [docs](https://optiflume.ai/docs)
- **Release notes:** [Releases](https://github.com/optiflume/feedback/releases) mirror the [changelog](https://optiflume.ai/docs/changelog)
- **Known issues and service status:** [optiflume.ai/status](https://optiflume.ai/status)
- **Security:** security@optiflume.ai, not an issue
- **Account and billing:** [optiflume.ai/support](https://optiflume.ai/support)

## Before you report

1. Update: OptiFlume checks for updates itself; `optiflume status` prints the version you have.
2. Run `optiflume doctor --bundle` and attach the file it saves to your Desktop. It holds no
   prompts, code, or names of your folders and files.
3. Say which tool (Cursor, Claude Code or Codex), whether in the editor panel or the terminal, and
   the macOS version.

## How issues move

`needs-info` → confirmed (labelled by area: `router`, `context-manager`, `guardian`, `console`,
`install`) → `fixed-in-next-release` → `released`, with the version in the closing comment.
We answer within two business days.
