# Learning Log

## S0: Setup (2026-10-10)

**Setup:** Temurin JDK 21, Git, IntelliJ and java-journey repo with roadmap layout and pushed to GitHub.

**What I Learned:** 
- 'git add' stages changes (the list for the next commit). 
- 'git commit' records that staged snapshot permanently, with a message.
- Git tracks files, not folders. `.gitkeep` is just a naming convention for a placeholder file, not a Git feature. `.gitignore` is the real feature.
- `git push -u origin main` links local `main` to `origin/main`, so a bare `git push` or `git pull` knows where to go.
- `git branch -d` only deletes a branch if its commits are reachable from the branch I'm standing on. `-D` forces it.

**Mistakes and surprises:**
- Called `git status` output an "error" when it was just "untracked files".
- Thought `.gitkeep` was built into Git.
- `git branch feature-x` creates a branch but doesn't switch to it (`git switch` does).