---
name: i-keep-forgetting-how-write-regex-d3c2
description: i keep forgetting how to write regex and i want a tool that lets me describe what i want to match in plain...
version: 0.1.0
license: Apache-2.0
---

# i-keep-forgetting-how-write-regex-d3c2

## Purpose

Use this skill to implement and operate: i keep forgetting how to write regex and i want a tool that lets me describe what i want to match in plain english and it gives me the regex. like 'match an email address' or 'find all dates in MM/DD/YYYY format'.

## Instructions

1. Run `./scripts/run.sh --help` to inspect supported inputs.
2. Run `./scripts/run.sh "<target>"` to generate an execution plan and recommended checks.
3. Review the emitted checklist and adapt it for your repository or environment.

## Inputs

- A target name or path as the main argument.
- Optional `--context` text to provide extra constraints.

## Outputs

- A structured checklist printed to stdout.
- Exit code `0` on success and non-zero on invalid usage.

## Constraints

- This starter implementation is intentionally minimal.
- Tailor the generated checklist before using it in production workflows.
