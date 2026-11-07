# IRA — Inspect Rebuild Applications

IRA is an agent skill for inspecting web applications and turning observed behavior into a specification, an improvement plan, and a verified rebuild when requested.

## Try it

Add the folder containing [SKILL.md](SKILL.md) and its companion files to an agent that supports skills. Invoke the skill as `$ira` in Codex with a scoped request.

> Use $ira to inspect supplier search in my demo portal. Map the filters, result states, and observable API behavior. Propose mobile improvements and write acceptance criteria. Stop at the assessment.

To request a rebuild, specify the workflows and target stack. IRA records what it observed, what it inferred, and what remains unknown. It reports visual and functional checks separately.

## Tools and templates

IRA can use browser inspection, screenshots, and sanitized network captures. [Reverse Engineer Anything](https://github.com/morluto/rea) (REA) is an optional upstream tool for bundle and browser analysis.

- [Tool selection](references/tool-selection.md)
- [Evidence, implementation, and verification templates](references/deliverables.md)

The workflow was exercised with an assessment scenario involving incomplete access. A full live inspection and rebuild trial is pending.

## License

[MIT](LICENSE).
