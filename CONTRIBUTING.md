# Contributing to Brexchat

These are some rough guidelines to follow if you want to help out with Brexchat!

## Got a Question or found a Problem?

If you're on the Tech for UK Slack team, say hi in the `brexchat` channel.

Alternatively, you can still help by reporting an [issue](https://github.com/TechForUK/brexchat/issues)

## Our Development Process

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

We use our own forks and [Github Flow](https://guides.github.com/introduction/flow/index.html) to deliver changes to the code:

1. Fork the repo and create your branch from `master`.
2. Include a descriptive message and the [Developer Certificate of Origin (DCO) sign-off](https://github.com/probot/dco#how-it-works) on all commit messages.
3. Issue a pull request!

## Coding Style

* There aren't any yet, but try and follow the style of the file(s) you're working on.

## Git cheatsheet

Configure your identity:

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

Clone your forked repository:

```
git clone <forked_repository>
```

Add original repository as the upstream remote:

```
git remote add upstream <original_repository>
```

Make your changes in a new git branch:

```
git fetch upstream master
git checkout -b my-fix-branch upstream/master
```

Add changes for committing:

```
git add -A
```

Commit your changes including the DCO sign-off:

```
git commit -s
```

Push your branch to GitHub:

```
git push origin my-fix-branch
```

### Git resources

* [Git Handbook](https://guides.github.com/introduction/git-handbook/)
* [Git Guide](http://rogerdudler.github.io/git-guide/)
* [Git homepage](https://www.git-scm.com)
