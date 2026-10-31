## Release Test Plans
- [0.6.1](plans/0.6.1/0.6.1.plan.md)

## Download & install test files
- **Test plans and associated QA scripts will fail unless the audio and library files have been installed**
- Use `git` to download these files -- **don't download .zip via GitHub Web UI**
- Out of date test files will generate invalid test results
    - Ensure your local repo is up to date
    - Ensure files on Zero are up to date with local repo
- Test files are located in this repo at `/music`

## When to publish a test run
- Certifying a build for public release
- Certifying a build for internal or Beta release
- Sharing triage of a bug report (internally or with outside reporter)

## How to publish a test run
- Create a run/[maj.min.hot.build]/[user]/[description] branch in the repo to store the results of your test run. Examples:
    - `run/0.6.1.r12/jaw/release-regression-0`
    - `run/0.7.0.r0/jaw/mixer-ui-test`
- Edit individual .md files with results, notes, etc.
- Commit those edits to the /run branch you created
- See [How to Publish Test Results](docs/how_to_execute_run.md) for further instructions

## UI Glossary
- [UI_GLOSSARY.md](UI_GLOSSARY.md)
