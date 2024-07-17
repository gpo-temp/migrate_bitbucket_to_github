# migrate_bitbucket_to_github
Simple Script for migrating repos from bitbucket to github

This is yet another migration script for migrating repos from
bitbucket to github. The other ones I found were great inspiration
but lacked certain features.

Features:
- Uses --mirror
- Allows running multiple times

Limitations:
- DOES NOT CHECK for usage of the github repo (will blow away changes)
- If changes are made to the github main branch it will not allow pushing the
  main branch

## Installation

```bash
curl -O https://raw.githubusercontent.com/gpo/migrate_bitbucket_to_github/main/bb2gh && chmod +x bb2gh
```

## Usage

```bash
./bb2gh <bitbucket_org> <github_org> --repo=<repo_name>
```

full help text (here)[https://github.com/gpo/migrate_bitbucket_to_github/blob/main/migrate_bitbucket_to_github#L7-L25]

