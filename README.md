# find-latest-tag-test

A minimal sandbox repo to verify the [`oprypin/find-latest-tag`](https://github.com/oprypin/find-latest-tag)
GitHub Action.

The workflow in `.github/workflows/latest-tag.yml` resolves the latest
**release** tag of [`kubevela/workflow`](https://github.com/kubevela/workflow)
and prints it to the run log.

## How to run

1. Push this repo to GitHub.
2. The workflow runs on every `push`, or trigger it manually from the
   **Actions** tab via **Run workflow** (`workflow_dispatch`).
3. Open the run and check the **Print latest tag** step output.
