# npm-version-increment
GitHub Action to increment the version number and push the tag to git.

Bumps the minor version if the branch is "master" or "main", and the patch version if anything else.

Outputs the current and new version numbers, and a string indicating the change type ('minor' or 'patch')
