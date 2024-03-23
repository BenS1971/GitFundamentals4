# git remote

When working with git, a **remote** is any git repository the is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub, for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repoisitories. Once stored remotely, you can bring that repository back down or you can share it with others.

**Note**: While repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

## Adding a remote
A remote be added with the `git remote add` commaned, followed by the name and location of the remote.

The name is the local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `git remote` command, followed by the name of the remote.

```
git remove origin
```

## Resources
- [Git Remote Documention](https://git-scm.com/git-remote)

---
[Back To Home](./README.md)