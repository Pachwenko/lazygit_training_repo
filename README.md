# lazygit_training_repo

Welcome to the Lazygit training exercises! The following scenarios are designed to help you practice common Git operations using Lazygit. Make sure you have Lazygit installed and configured on your system before starting.

## Tips for Using Lazygit
	•	Navigation: Use the arrow keys to navigate between files, branches, and commit history.
	•	Help: Press ? at any time in Lazygit to see a list of available commands.
	•	Staging/Unstaging: Lazygit makes it easy to stage changes—simply select the file and press s.

---

### Scenario 1: Creating a New Branch and Pushing a New File

In this scenario, you’ll create a new branch, add a file with some random data, commit the change, and push the branch to the remote repository.

Steps:
	1.	Create a New Branch:
	•	Open Lazygit in your terminal.
	•	Press b to open the branch menu.
	•	Create a new branch by selecting “Create new branch” and name it appropriately (e.g., feature/new-file).
	2.	Create a New File and Add Random Data:
	•	Outside Lazygit (using your favorite text editor), create a new file (for example, random.txt) in the repository.
	•	Add some random content to this file.
	3.	Commit the New File:
	•	Return to Lazygit.
	•	You should see your new file in the unstaged changes panel.
	•	Open the Files tab by pressing `2`
	•	Stage the file by pressing <space> on it.
	•	Once staged, press c to commit. Enter a commit message and a fake [] ticket link in the message section
	4.	Push the File to Remote:
	•	After committing, press capital P to push your changes

---

### Scenario 2: Merging a Branch with Conflicts and Resolving Them

In this scenario, you’ll create another branch and merge changes from the branch named conflicting_history into your new branch. You will then fix any merge conflicts that arise and push your updated branch.

Steps:
	1.	Create Another New Branch:
	•	In Lazygit, press b to create a new branch. Name it (e.g., feature/merge-conflicts).
	2.	Merge Changes from conflicting_history:
	•	With your new branch checked out, press m to bring up the merge menu.
	•	Select the branch named conflicting_history to merge into your current branch.
	•	Lazygit will show you the merge process and any conflicts if they arise.
	3.	Resolve Merge Conflicts:
	•	If merge conflicts occur, Lazygit will highlight the files with conflicts.
	•	Open each conflicted file (using your text editor) and resolve the conflicts manually.
	•	After resolving the conflicts, return to Lazygit.
	•	Stage the resolved files by selecting them and pressing s.
	•	Commit the merge by pressing c and providing a commit message like “Resolve merge conflicts with conflicting_history”.
	4.	Push Your Updated Branch:
	•	Once the merge commit is complete, press p in Lazygit.
	•	Push your updated branch to the remote repository.


---

### Scenario 3: Alias lazygit to lg

Not really for training, but since this is LAZY git we don't want to type more than necessary.

Add this to your shell aliases:

```
alias lg=lazygit
```
