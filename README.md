# Workflow

Create your own branch from origin/draft.

```
$ git checkout -B your_first_name origin/draft
$ git push -u origin your_first_name
```

Create a pull request from your branch to origin on GitHub.

To synchronize changes in from origin/draft:
```
  $ git checkout -B your_first_name
  $ git fetch
  $ git rebase origin/draft
```

To update your branch
```
  $ git checkout -B your_first_name
  $ hackity, hack, hack
  $ git add . && git commit -am 'Brief description of changes.'
  $ git push
```

Never push to master; that's a publish event that will generate the book and notify purchasers.


