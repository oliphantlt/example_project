# This is an example project

### Markdown Basics

You should know how to format text (bold, italic, headings, numbered and bulleted lists), include links and images, and include coding blocks.  If you want to learn more go to [Githubs's Markdown Site](https://guides.github.com/features/mastering-markdown/).

Example code blocks:

```javascript
function blah(x) {
	print("hello");
}
```

```python
def blah(x):
   print("Hello")
```

### Git Basics

You should know how to
* initialize a project
* Add a file to be maanged
* Commit a file along with a message
* Look at the log along with
	* --graph
	* --stat
	* --patch
* status to see what is in the staging area

### Git Undoing Things

* status (to see what is staged for a commit)
* "commit --amend" (to add additional files to previous commit)
* "reset HEAD \<file\>" -- to unstage a file
* "checkout -- \<file\>" -- to discard changes for a file and revert back to last checked out version of file.


### Git Branches

Branching means you diverge from the main line of development and continue to work without messing wiht that main line.  You can create a branch and then make changes that will be recorded within that branch.

Me trying to add via a testing branch.

### Git Remotes

* `git remote -v` (to see the list of remote repositories)
* `git remote add <shortname> <url>` to link a remote repository to your local project.  The \<shortname\> can be used in the future to refer to the remote repository.
* `git fetch <remote>` downloads data from the remote project which you don't have yet.  After this command you have references to all the branches from that remote, which you can merge or inspect at any time.

