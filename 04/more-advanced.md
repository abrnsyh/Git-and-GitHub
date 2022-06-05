1. git revert should be used to undo changes on a public branch, and git reset should be reserved for undoing changes on a private branch.
2. Git rebase moves a feature branch into a master. Git merge adds a new commit, preserving the history.
3. The key difference between git stash pop and apply involves the stash history. When a developer uses the git stash apply command, the most recently saved stash overwrites files in the current working tree but leaves the stash history alone. In contrast, the pop command restores files but then deletes the applied stash.
