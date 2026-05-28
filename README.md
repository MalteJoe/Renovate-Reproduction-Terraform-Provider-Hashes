# Renovate Discussion [#43641](https://github.com/renovatebot/renovate/discussions/43641)

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior
* On GitLab, Renovate stops mid-branch and mid-repository silently and exiting with Code `0`
  ** Link To Reproduction Repo: https://gitlab.com/MalteJoe/Renovate-Reproduction-Terraform-Provider-Hashes
* When using autodiscover, this also leads to multiple repositories not being processed

## Expected behavior
* The update should work just like on GitHub (Link to Reproduction: https://github.com/MalteJoe/Renovate-Reproduction-Terraform-Provider-Hashes)
* Or the error should be logged and handled, so other repositories/branches are not affected

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/43641
