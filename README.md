# hadolint-sarif-example

An example of using `hadolint` and SARIF integration with Github.

The [pull request](https://github.com/psastras/hadolint-sarif-example/pull/1/files)
of this example repository illustrates coupling SARIF output with Github annotations
allowing `hadolint` errors to appear directly in the pull request changes.

The Github Action workflow `main.yml` also uploads the SARIF results to Github
storing them in the Security tab via Github Advanced Security.
