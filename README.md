# Git workshop
## Local
There are commands and notes that were covered during the workshop.
Hello there
second line
- `git commit`: open your default editor to type a commit message and commit changes
	- `git commit -m  "MESSAGE"`: wrute a one line message and commit in 1 step
- `git log`: to see commit messages from reverse chronological order
- `git diff`: shows you the difference beteween current state and last commit
	- git diff --staged shows the differences between current state and last commit that were in staging area

- `git checkout  <HASH> <FILE>`: reverts <FILE? back to the state in <HASH>
	- `git checkout HEAD~<NUM> <FILE>`: reverts <FILE> back to state in HEAD~<NUM>
	- `git check out <HASH>`: moves HEAD to <HASH> (moves entire state/folder/snapshot)
		- `git checkout master`: goes back to master from detached HEAD state
- `HEAD`: tell you where you are currently looking
- `git restore <FILE>`: throws away changes from <FILE>
	- can also use this to unstage from staging area
	- older versions of git use `git rest`
## Remote
- `git push`

- `.gitignore`: special file git uses to ingore files/folders
	- `git add -f <FILE>` force add a file that is ignored
- `git remote add <NAME> <URL>`: adds the reference <NAME> to the <URL>
	- `git remote add origin <SSH URL>`
- `git push <WHERE> <WHAT>`: pushes <WHAT> to <WHERE>
	- `git push origin master`
	- do this once for rstudio: `git push -u origin master` 
- `git long --oneline`: will now show referenes to the remote eg origin/master

	- `git log --oneline --graph --all`: shows you the entire history and makes it p>

## New branch

