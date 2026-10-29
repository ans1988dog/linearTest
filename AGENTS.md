# Repository workflow

## Pull requests

After completing any requested code change:

1. Commit the finished changes on the current branch.
2. Push the branch to the `origin` GitHub remote.
3. Create a GitHub pull request with `gh pr create`, or update the existing pull request when the branch already has one.
4. Verify the pull request on GitHub with `gh pr view` and include its GitHub URL in the final response.

Do not treat locally generated pull-request metadata as a submitted pull request. A task is not considered submitted until the branch is pushed and the pull request is visible on GitHub.
