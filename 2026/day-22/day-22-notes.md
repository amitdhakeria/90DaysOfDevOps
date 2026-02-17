What is the difference between git add and git commit?

Git add: This command is used to add the files in the staging area of the Git. That means Git is tracking the file, it knows file is there and git is tracking it but not commited yet.

Git commit: it saves the changes permanantly into the GIT history.

Think like this:

git add = selecting items into cart 🛒

git commit = placing the final order ✅


Q2: What does staging area do? Why doesn't Git commit directly?
Ans: The staging area(also called index) is like the middle area between the working file and the final commit.

It allows you to:
 Select specific files
 select partial chnages
 control exactly what goes into the commit.

Why not commit directly?

Becuase sometime, if we changes 5 files and wanted to commit only five file for now. So it gives us the flexibility.


Q3: What information "git log" shows you?
Ans: "git log" shows the commit history.

It shows:

- Commit ID (SHA)
- Author name
- Date & Time
- Commit message

It helps you track:

- who made chnages
- When chnages were made
- What chnages were described.


Q4: What is the .git/ folder and what happen if you delete it?

It contains:

- All commit history
- Branch information
- Configuration
- Logs
- Object database

If you delete .git/: 

❌ Your project is no longer a git repository.
❌ All commit history is gone
❌ Branches are gone.

Your code file will still be there but version control willl be completly removed. It becomes a normal folder again.

Q5: What is the diffrenece between working directory, staging area, Repository?


🟢 Working directory

- The actual project file.
- where you modify the file
- Example: you modify app.py


🟡 Staging Area:

- Temporary holding area
- Files you selected using "git add"
- Waiting to be commited


🔵 Repository:

- .git database
- Stores commited history permanently


 

