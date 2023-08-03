# npm-version-increment
GitHub Action to increment the version number and push the tag to git.

Bumps the minor version if the branch is "master" or "main", and the patch version if anything else.

Outputs the current and new version numbers, and a string indicating the change type ('minor' or 'patch')

TODO - Many other actions on the marketplace allow the use of a "v1" version reference to indicate "latest v1 including minor and patch versions." This is achieved by creating a v1 ref and then updating it to point to the latest commit on each build. Discussion and links to an example here - https://stackoverflow.com/questions/74962405/how-does-github-actions-workflow-resolve-minor-versions-of-an-actions
