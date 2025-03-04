### Merging:

- After completing the feature-login branch, merge it back into the main branch.

---

### Questions

1. What command will you use to merge the feature-login branch into the main branch?
2. What will you do if there are merge conflicts?

---

### Answer

1. First go back to main `git checkout main` then `git merge feature-login`

2. `git add <conflict-filename>` then `git commit -m "Resolve merge conflicts and merge feature-login"`

---

### Remote Repo

#### To push to remote repository after added it

1. add it `git remote add origin git@github.com:NourElDin023/day-2-lab.git`
2. `git push origin main`
