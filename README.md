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

