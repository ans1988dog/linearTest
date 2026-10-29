# Repository workflow

## Pull requests

After completing any requested code change:

1. Commit the finished changes on the current branch.
2. Push the branch to the `origin` GitHub remote.
3. Create a GitHub pull request with `gh pr create`, or update the existing pull request when the branch already has one.
4. Verify the pull request on GitHub with `gh pr view`.
5. After required checks pass, merge the pull request automatically with `gh pr merge`. If branch protection prevents an immediate merge, enable auto-merge instead.
6. Verify that the pull request is merged (or that auto-merge is enabled) with `gh pr view`, and include its GitHub URL and final state in the final response.

Do not treat locally generated pull-request metadata as a submitted pull request. A task is not considered complete until the branch is pushed, the pull request is visible on GitHub, and the pull request has been merged or scheduled for automatic merge.
