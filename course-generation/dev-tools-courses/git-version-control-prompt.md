📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Dev Tools Prompts Index`](./README.md) | 📖 [`Course Output: Git & Version Control`](https://github.com/worapha05/dev-tools-courses/blob/main/git-version-control/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Software Engineer and Devops Workflow Architect specializing in distributed version control and repository management. Help me create a complete "Zero to Expert" self-learning bootcamp for Advanced Git and Enterprise Collaborative Workflows across GitHub, GitLab, and Bitbucket platforms.

# Target Structure
Generate all files inside a folder named `/git-version-control`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกการทำงานเบื้องหลังของ Git และแนวคิดการบริหารจัดการ Source Code อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: ตัวอย่างคำสั่ง Git CLI, ไฟล์การตั้งค่า (.gitignore, .gitattributes) และตัวอย่างโครงสร้างไฟล์สคริปต์ Git Hooks
3. `LAB.md`: โจทย์ทดสอบการจำลองสถานการณ์การทำงานจริง (เช่น การกู้คืนโค้ดที่หาย, การแก้ Merge Conflict ซับซ้อน และการบริหารสาขาโค้ดในทีมใหญ่) เป็นภาษาไทย พร้อมเฉลยลำดับคำสั่งอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Git Core Mechanics & Local Repository)
- Git Internal Architecture: How Git tracks changes (The Three States: Working Directory, Staging Area, Local Repository). Understanding Commits, Hashes, and the HEAD pointer.
- Essential Git CLI: Mastering `git init`, `status`, `add`, `commit`, `log`, `diff`, `checkout` (vs `switch`/`restore`), and `clone`.
- Undoing Changes Basics: Utilizing `git reset` (soft, mixed, hard), `git revert` to undo commits safely, and managing tracked/untracked files via `.gitignore` configuration.

## 2. Intermediate Level (Remote Collaboration & Branching Strategies)
- Branch Management: Branching creation, merging (`git merge` fast-forward vs three-way merge), and mastering `git stash` for temporary work isolation.
- Distributed Collaboration: Working with remotes (`git remote`, `fetch`, `pull`, `push`), tracking upstream branches, and managing remote authentication (SSH keys vs Personal Access Tokens).
- Platform Workflows (GitHub / GitLab / Bitbucket): The anatomy of a perfect Pull Request / Merge Request. Code Review culture, requesting changes, managing branch protections, and enforcing status checks before merging.

## 3. Expert Level (Enterprise Git Workflows, Conflict Resolution & Repository Hardening)
- Advanced Branching Topologies: Implementing and comparing **Git Flow**, **GitHub Flow**, and **Trunk-Based Development** for high-velocity teams.
- Code Surgery & History Rewriting: Interactive Rebasing (`git rebase -i`), Squashing commits, Cherry-Picking specific changes (`git cherry-pick`), and utilizing `git reflog` to recover deleted branches or lost commits.
- Conflict Engineering: Deep dive into complex Merge Conflicts resolution, understanding conflict markers, and using 3-way diff tools.
- Repository Automation & Security: Implementing client-side and server-side **Git Hooks** (pre-commit linters, commit-msg verification). Enforcing security policies (preventing credential leaks, scanning secrets), repository size optimization, and advanced usage of Git Submodules/Monorepo code management.
```
