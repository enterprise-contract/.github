# .github

This repository stores GitHub specific information that applies to all the repositories within the
enterprise-contract GitHub organization.

## Community Health Files

Currently, this repostory defines the following [community health
files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file):

* [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
* [CONTRIBUTING.md](./CONTRIBUTING.md)
* [SECURITY.md](./SECURITY.md)

## Required Workflows

The [workflows](./workflows) defined in this repository are meant to be used by other repositories
within this organization. They should be included in a [repository
ruleset](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)
at the organization level. This is not done automatically. When adding a new workflow, be sure to
also update the corresponding ruleset
[here](https://github.com/organizations/enterprise-contract/settings/rules).
