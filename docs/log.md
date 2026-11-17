# Engineering Log

## 2026-11-17 (Day 1)
**Goal:** Set up the repo and understand the raw signal.

**Done:**
-repo structure, .gitignore, README skeleton, first commit pushed. 

**Observations:**
- Ran git init in the wrong folder (and inside docs/). Check pwd first.
GitHub doesn’t accept passwords for Git. Use gh auth login + gh auth setup-git.
~/.config was owned by root (from an old sudo install). Fixed with chown.
git rm --cached <file

**Questions / open issues:**
- Why resample to 1 kHz, and why resample_poly instead of decimating by 2?
- How would I defend Python prototyping vs designing directly in C?

**Next:**
-get to the interesting part: the conda environment, loading the data, and the first EMG plots
