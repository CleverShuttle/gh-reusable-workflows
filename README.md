# GitHub Reusable-Workflows

The repository provides all GitHub reusable-workflows. [Click here for the documentation](https://clevershuttle.atlassian.net/wiki/spaces/CI/pages/3607494720/Workflows)

## Security hint

Use actions or intermediate environment variables and double quote shell variables
([see examples on GitHub](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#good-practices-for-mitigating-script-injection-attacks))
to [mitigate script injections](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#understanding-the-risk-of-script-injections).

## Development

* You can change the reusable workflows and push to master (potentially via a PR) which updates the tag that the GitHub workflows refer to. Your changes are effective globally on the next run of the reusable workflow.
* You may create a PR and refer to the branch of the PR in a workflow of a GitHub repository by using `@<branch name>` instead of `@v1` when referring to the reusable workflow. This allows you to test risky changes.
* When [act#826](https://github.com/nektos/act/issues/826) has been solved you may also [use act to develop the reusable workflow locally](https://clevershuttle.atlassian.net/wiki/spaces/CI/pages/3613688270/How-to+Run+your+GitHub+Actions+locally)

## Code owners

See [CODEOWNERS](CODEOWNERS)


