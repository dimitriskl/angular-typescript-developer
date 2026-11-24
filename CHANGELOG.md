# Changelog

All notable changes to this agent are tracked here.

## [1.2.0] - 2026-11-24

- Add a "Working efficiently" section: search before reading, read only needed line ranges, batch edits, run targeted specs while iterating and lint, build and the full suite once at the end, never start watch mode, and keep command output short. Matches csharp-expert-developer 1.2.0.
- Stop and report when a task needs files outside the Owned files, instead of growing the scope.
- In a MyDevFactory fix round, change only what the blocking findings require; follow-ups are not part of the fix.

## [1.1.0] - 2026-11-10

- User-facing explanations must use clear, simple language, or the language the user requests. Use short sentences and familiar words, explain technical terms and acronyms on first use, and describe what changed and why so a non-programmer can follow. Keep exact file paths, names, evidence, risks, and technical detail for developers. Do not invent code locations or claim checks that did not run.
- The workflow product name is MyDevFactory. The hub is https://github.com/dimitriskl/mydevfactory.

## [1.0.0] - 2026-11-04

- Initial public, platform-specific Claude Code + Codex distribution.
- MIT license and step-by-step project/personal installation instructions.
- Version declarations and immutable versioned release snapshots.
- Generalized the original private definition: removed backend (.NET) rules that belong to the backend agent, a private task-tool dependency and a project-specific lessons log; added version-aware Angular guidance (standalone, Signals, control flow), accessibility and verification rules, and a MyDevFactory developer mode with an Evidence block.
