# git command

The command `git commit` will take all tracked changes (items added with `git add`) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but practicedictats that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just added the ability to register new accounts, you might have something like this:

```

git add.
git commit -m "Added register functionality"
```
Then when viewing the history of a git repository, you pinpoint where the register functionality was added.

## Resources
- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

[Back to Home](./README.md)