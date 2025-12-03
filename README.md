# -Frontend-version-control-task-SeanMosesOkonofua
Version Control. Creating repositories, cloning repositories, creating branches, committing and reverting commits, pulling and pushing changes downstream and upstream, fetching, merging and renaming branches, creating, reviewing merging, reverting pull requests etc.
feature-footer
feature-header
$ git clone [repository-url]
$ git add .
$ git commit -m "feat: initial commit with project setup and README"
$ git push origin main
$ git checkout -b feature-header
$ git checkout -b feature-footer
$ git commit -m "feat(header): add initial HTML structure and header element"
$ git add index.html style.css
$ git commit -m "style(header): apply basic styling to the header section"
$ git commit -am "feat(header): add navigation links to header"
$ git push -u origin feature-header
$ git checkout main
$ git pull origin main
$ git checkout feature-footer
$ git commit -am "feat(footer): add footer structure to index.html"
$ git commit -am "feat(footer): add copyright and social links"
$ git commit -am "style(footer): add minor styling to distinguish footer"
$ git push -u origin feature-footer
$ git commit -am "fix(header): updated color based on PR review"
$ git push
$ git checkout main
$ git commit -am "fix: an intentional minor error commit to demonstrate revert"
$ git push origin main
$ git log --oneline
$ git revert [commit-hash-of-error]
$ git push origin main
$ git checkout feature-header
$ git branch -m feat-navbar
$ git push origin --delete feature-header
$ git push -u origin feat-navbar
git checkout -b, git commit -m, git push, git pull, git revert.
