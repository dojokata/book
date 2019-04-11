&copy; 2019 David Laribee.

Contributions are the copyright of their respective authors.

## Contributing

Create your own branch from origin/draft.

`$ git checkout -B your_first_name origin/draft`

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
  ... make changes
  $ git push
```

Never push to master. That's a publish event that will generate the book and notify purchasers.