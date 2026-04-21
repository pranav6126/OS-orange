# Answers

## Q5
The HEAD file stores a reference to the current branch (usually main).  
It does not store the commit hash directly, but points to a branch file.  
The branch file then stores the latest commit hash.

## Q6
The index file acts as a staging area.  
It stores metadata such as file mode, hash, timestamp, size, and filename.  
It is used to track changes before creating a commit.
