# Split Commit - Fix added and deleted files to be renamed files

https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History#_splitting_a_commit

Don't break the git commit history when file names change

Show diff that displays the problem of 'new' files and 'deleted' files when
really just a rename of the file happened with some content changes.

## Visual Summary
```
Add image or other visual representations...
```

## Summary
* Make a feature branch
* Make changes to a file and rename it in the process
* Commit the renamed file and any other changes which include deleting the old
    file
* Add more commits
* Rebase to fix the new and deleted file to just be a renamed file with changes

# Exercise

## [Step Title]
[Step Description]
