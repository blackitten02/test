Hello World!!

Git - a system that tracks changes in your files over time

Repo:

&#x09;-A normal folder + hidden .git folder

&#x09;-.git stores all history, commits, branches

Git Workflow:

&#x09;-working directory -> staging area -> Repository

&#x09;	

&#x09;1.Working directory:

&#x09;	-Your normal files

&#x09;		</>Bash

&#x09;		README.md

&#x09;		</>Bash

&#x09;		echo "Hello World" > README.md

&#x09;2.Staging area(git add):

&#x09;		</>Bash

&#x09;	"Git, I want to include these changes in the next save"

&#x09;	. = everything in folder

&#x09;	You ain't saving yet, just preparing

&#x09;3.Commit (git commit):

&#x09;		</>Bash	

&#x09;	"Save a snapshot of my staged changes"

&#x09;		-m = message describing the change

&#x09;	This creates a commit(like a checkpoint)

&#x09;4.Remote (GitHub):

&#x09;	Your code is still only on your computer until you push

&#x09;5.Push(git push):

&#x09;		</>Bash

&#x09;		git push origin main

&#x09;	origin = your GitHub repo

&#x09;	main = branch name

&#x09;	"send my commits to GitHub"

&#x09;	

&#x09;	origin:

&#x09;		-when you cloned:

&#x09;			</>Bash

&#x09;			git clone https://github.com/blackitten02/test.git

&#x09;		-git automatically set:

&#x09;			</>Bash

&#x09;			origin = your GitHub repo URL

&#x09;		-check it:

&#x09;			git remote -v

&#x09;	main:

&#x09;		A branch = a version of your project

&#x09;		main = default branch / your main timeline

What you did:

&#x09;1.Create file

&#x09;2.Tell Git: "track this" (add)

&#x09;3.Save snapshot (commit)

&#x09;4.Upload to GitHub (push)



