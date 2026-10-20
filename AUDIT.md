# Quarterly Engineering Report — GitHub Side — 2026 Q4

## 1. Account Audit

**Signed-in account:** HeziLiu — https://github.com/HeziLiu
- Display name: Hezi Liu
- Company: BUPT/GZU
- Location: Beijing/Guiyang
- Email: tackic@icloud.com
- Bio: "treat me like a tree"
- Account created: 2017-05-22T10:11:01Z

**Live profile numbers (as returned by the API, unrounded):**
- Public repositories: 4
- Public gists: 0
- Followers: 5
- Following: 5

**Public user search — outside-searcher view for "HeziLiu":**
Total count: 4 (complete results, `incomplete_results: false`)

1. HeziLiu — https://github.com/HeziLiu (id 28861483)
2. heziliustc — https://github.com/heziliustc (id 33093911)
3. heziliuaa — https://github.com/heziliuaa (id 223793225)
4. heziliu00-oss — https://github.com/heziliu00-oss (id 316041917)

## 2. Public Repositories Under HeziLiu

Repository search returned **4** public repositories (including 2 forks), matching the profile's public repository count of 4:

| # | Repository | Description | Language | Default branch | Fork | Created | Last updated |
|---|------------|-------------|----------|----------------|------|---------|--------------|
| 1 | Little-rookie | Undergraduate coursework | Java | master | No | 2018-05-15 | 2019-06-02 |
| 2 | CodingInterviewChinese2 | 《剑指Offer》第二版源代码 | C++ | master | Yes | 2019-03-12 | 2019-03-12 |
| 3 | awesome-chatgpt-prompts-zh | ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。 | — | main | Yes | 2023-04-14 | 2023-04-14 |
| 4 | Big-Buzzard | For future.... | — | master | No | 2018-05-15 | 2018-05-17 |

Links:
- https://github.com/HeziLiu/Little-rookie
- https://github.com/HeziLiu/CodingInterviewChinese2
- https://github.com/HeziLiu/awesome-chatgpt-prompts-zh
- https://github.com/HeziLiu/Big-Buzzard

## 3. Local Scratch Repository Baseline (this quarter)

- Location: workspace root
- Current branch: master
- Working tree: clean (nothing to commit)
- Most recent commit:
  - Short hash: 3c54245
  - Full hash: 3c54245d1ec850f0d3bc36cab971e08bf4962d27
  - Message: "Initial synthetic state"
  - Author: MCP World <synth@mcp-world.local>
  - Date: 2026-10-20 05:00:19+00:00

Note: an earlier version of these notes recorded baseline 914ed78 (2026-10-20 03:41:34+00:00). The scratch repository was subsequently re-seeded; the baseline above (3c54245) was re-read live at report time and is the operative quarter baseline.

## 4. Archive Repository & Workflow Status

- Archive repository: **quarterly-audit-2026-q4** (public) — https://github.com/mcpmark-eval-liuhezi/quarterly-audit-2026-q4
- Default branch: **main**
- Verified branch list (actually enumerated, not assumed): `main` and `audit-log` (audit-log was created on top of the default branch)
- `AUDIT.md` (this file) present on `audit-log`
- `draft.md` placeholder was kept on `audit-log` while the notes were assembled, then removed via commit "Remove draft placeholder" (86752a5) — only the finished notes remain
- CI workflow: `.github/workflows/ci.yml` on `main` — manual trigger only (`workflow_dispatch`), a checkout step plus a no-op echo
- Workflow registration: **confirmed** — workflow id 390122267, name "CI", state `active`, path `.github/workflows/ci.yml`
- Workflow run count: **0** (the workflow is manual-trigger-only and has never been dispatched)
- Audit checklist: issue #1 "Audit checklist", closed as completed with a closing summary comment

## 5. Notes

- The archive repository lives under the organization `mcpmark-eval-liuhezi` rather than the personal account: personal repository creation was rejected by the token (403 Resource not accessible by personal access token), and the organization route was the permitted path.
- Gist copy (`audit-2026-q4.md`): **could not be created** — `POST /gists` was rejected by the token scope (403 Resource not accessible by personal access token). Re-verified this session: the account holds no existing gists (authenticated listing and the public user listing both returned empty), so there is nothing to update, and gists cannot be created under an organization. This repository (with AUDIT.md on `audit-log`) therefore serves as the permanent home for the 2026 Q4 GitHub-side report.
