**Conventional commits are necessary**

- Make repo Commitizen friendly so it's easy to make convential commits
- Use commitlint with Husky to make sure commits actually follow the desired format (locally and on CI, see https://commitlint.js.org/#/guides-ci-setup)

**When any branch is pushed to**

1. Check formatting of commit messages
2. Run test, prettier, code coverage, and lint
3. Run build

**When main is pushed to**

1. Run test, prettier, and lint
2. Run build
3. Use semantic-release
