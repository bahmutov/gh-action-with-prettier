# gh-action-with-prettier

> Playing with Prettier that runs inside a GitHub Action

If you forget to run `npm run format` before committing and pushing source code, no big deal. GitHub action defined in [.github/workflows/ci.yml](.github/workflows/ci.yml) installs NPM dependencies, runs the format script, and if there are any changed files, commits them and pushes back to master. Under the hood it uses [mikeal/publish-to-github-action@master](https://github.com/mikeal/publish-to-github-action) action.

- [Trying GitHub Actions](https://glebbahmutov.com/blog/trying-github-actions/) blog post
