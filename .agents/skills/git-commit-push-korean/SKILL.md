---
name: git-commit-push-korean
description: "Create small logical git commits with messages in the form '<English category>: <Korean message>', then push the branch. Use when the user asks to commit, split changes into multiple commits, or push code."
---

# Git Commit and Push in Korean

## When to use this skill

Use this skill when the user wants:

- Git changes saved as commits
- Commit history split into small, logical units
- Commit messages written as `<English category>: <Korean message>`
- The branch pushed after committing

## Core rules

- Always inspect the working tree before committing.
- Prefer multiple small commits over one large commit when the changes are logically separable.
- Keep each commit focused on one purpose, such as one feature, one fix, one refactor, or one documentation update.
- Do not mix unrelated changes in the same commit.
- Do not rewrite history or force-push unless the user explicitly asks for it.
- If the branch has no upstream, set it on the first push.

## Commit message format

Use this exact structure:

```text
<english-category>: <korean-message>
```

Examples:

- `feat: 로그인 검증 로직을 추가`
- `fix: 중복 요청으로 인한 오류를 수정`
- `docs: 사용 방법 안내를 보강`
- `refactor: 컴포넌트 구조를 정리`
- `chore: 불필요한 파일을 정리`

## Recommended categories

Prefer standard conventional-commit categories:

- `feat`
- `fix`
- `docs`
- `refactor`
- `test`
- `chore`
- `build`
- `ci`
- `perf`
- `style`
- `revert`

## Workflow

1. Check the current branch, status, and diff.
2. Group changes by intent and dependency.
3. Split the work into the smallest set of coherent commits.
4. Stage and commit one group at a time.
5. Verify the log to ensure each commit message follows the format.
6. Push the branch after all commits are created.

## How to split commits

- Use separate commits for separate concerns.
- If one file contains multiple unrelated changes, stage hunks selectively.
- If a change depends on another change, keep them in the same logical sequence.
- If a clean split is not possible without harming correctness, keep the commit boundary where the code remains understandable and buildable.

## Push rules

- Push only after the commit sequence is complete.
- If the branch already tracks a remote, use a normal push.
- If the branch does not track a remote, use `git push -u origin <branch>`.
- If the push fails because the remote has moved, stop and report the conflict instead of forcing a push.

## Reporting back to the user

- Summarize each commit in order.
- Include the commit message and what logical change it contains.
- Mention the branch name and whether the push succeeded.
- If the work could not be split cleanly, explain the constraint briefly and describe the grouping that was used.

## Quality bar

- Favor clarity over brevity in commit history.
- Keep the message body short unless extra context is necessary.
- Use Korean for the subject after the category, but keep the category in English.
