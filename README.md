# Superpowers Prompt Collection

This repository turns the Superpowers software-development methodology into a reusable set of text prompts for AI coding assistants.

The goal is to make an AI assistant behave more like a disciplined engineering partner:
- ask questions before guessing
- design before coding
- write a plan for multi-step work
- write failing tests before implementation
- verify results before claiming success
- review before finalizing

## Workflow

1. Clarify the problem and goals
2. Design the approach
3. Write an implementation plan
4. Write failing tests
5. Implement the minimal correct fix
6. Verify with evidence
7. Review the work
8. Finalize and report status

## Files

- `00-QUICK-START.md` — quick copy-paste prompt for everyday use
- `01-SUPERPOWERS-SYSTEM-PROMPT.md` — requirement clarification and user-alignment stage
- `02-DESIGN-AND-SCOPE-CLARIFICATION.md` — architecture and design stage
- `03-PLAN-WRITING.md` — implementation planning stage
- `04-TEST-DRIVEN-DEVELOPMENT.md` — test-first workflow
- `05-CODE-REVIEW-SELF-CHECK.md` — review and quality gate
- `06-VERIFICATION-AND-FINALIZE.md` — verification and delivery

## How to use

Copy the file you want into your AI tool's system prompt or start-of-chat prompt. For the most disciplined workflow, combine them in sequence:

1. Start with `01-SUPERPOWERS-SYSTEM-PROMPT.md`
2. Move to `02-*` when the task is non-trivial
3. Move to `03-*` for multi-step work
4. Use `04-*` before implementation
5. Use `05-*` before final output
6. Use `06-*` for final verification and summary

This is a text-only alternative to the plugin-based Superpowers system.
