# dotnet-tool-update-test

Test repo showing how to use GitHub Actions to check for dotnet local tool updates and PR them similar to Dependabot.

## Classic personal access tokens

Your PAT will need the following scopes:

- `repo`

## Fine-grained personal access tokens

Your PAT will need the following repository permissions:

Permission | Access
:-- | :--
actions | read and write
contents | read and write
metadata | read-only
pull requests | read and write
