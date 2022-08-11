To run:

- clone and checkout to repo
- create local remote
  ```bash
  git init --bare ../git-diff-remote.git
  git remote add testing ../git-diff-remote.git
  ```
- run `./test`

To dev:

- edit `./git-files-push` implementation
- commit/amend changes
- run `./test`
