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
- If changes are made to the main branch it will not allow pushing the
  main branch

