## Contributing

[fork]: https://github.com/github/codeql-action/fork
[pr]: https://github.com/github/codeql-action/compare
[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE).

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

## Development and Testing

Before you start, ensure that you have a recent version of node installed. You can see which version of node is used by the action in `init/action.yml`.

### Common tasks

* Transpile the TypeScript to JavaScript: `npm run build`.  Note that the JavaScript files are committed to git.
* Run tests: `npm run test`.  You’ll need to ensure that the JavaScript files are up-to-date first by running the command above.
* Run the linter: `npm run lint`.

### Running the action

To see the effect of your changes and to test them, push your changes in a branch and then look at the [Actions output](https://github.com/github/codeql-action/actions) for that branch.  You can also exercise the code locally by running the automated tests.

### Integration tests

As well as the unit tests (see _Common tasks_ above), there are integration tests, defined in `.github/workflows/integration-testing.yml`.  These are run by a CI check.  Depending on the change you’re making, you may want to add a test to this file or extend an existing one.

## Submitting a pull request

1. [Fork][fork] and clone the repository
2. Create a new branch: `git checkout -b my-branch-name`
3. Make your change, add tests, and make sure the tests still pass
4. Push to your fork and [submit a pull request][pr]
5. Pat your self on the back and wait for your pull request to be reviewed and merged.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Write tests.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write a [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
