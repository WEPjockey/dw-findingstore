# Contributions Welcome

First off, thank you for considering contributing to the Findingstore! This resource is a simple project, but has plenty of room for improvement. Many features of Github's webhook implementation are yet to be built into the Findingstore, and all contributions are welcome.

If you're just looking for quick feedback for an idea or proposal, feel free to open an
[issue](https://github.com/homedepot/dw-findingstore/issues/new).

Follow the [contribution workflow](#contribution-workflow) for submitting your
changes to the Findingstore codebase. If you want to receive high-level but still
commit-based feedback for a contribution, follow the
[request for comments](#request-for-comments) steps instead.

## Contribution Workflow

The Findingstore uses the “fork-and-pull” development model. Follow these steps if
you want to merge your changes to the Findingstore:

1. Within your fork of the
   [Findingstore](https://github.com/homedepot/dw-findingstore), create a
   branch for your contribution. Use a meaningful name.
2. Create your contribution, meeting all
   [contribution quality standards](#contribution-quality-standards)
3. [Create a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)
   against the master branch of the Findingstore repository.
4. Add a reviewer to your pull request. Work with your reviewer to address any comments and obtain an approval.
   To update your pull request amend existing commits whenever applicable and
   then push the new changes to your pull request branch.
5. Once the pull request is approved, one of the [maintainers](MAINTAINERS.md). will merge it.

## Contribution Quality Standards

Your contribution needs to meet the following standards:

- Separate each **logical change** into its own commit.
- Add a descriptive message for each commit. Follow
  [commit message best practices](https://github.com/erlang/otp/wiki/writing-good-commit-messages).
- Document your pull requests. Include the reasoning behind each change, and
  the testing done.
- Acknowledge the [Apache 2.0 license](LICENSE). Ensure that every file in your pull request has a
  header referring to the repository license file.
