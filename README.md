# SENG363 Lab 9 – GitHub Actions CI/CD

Automatically performs **checkout, build, five unit tests and local development-sandbox deployment** on each push and when triggered manually.

## How to use
1. Upload the repository files preserving the paths, including `.github/workflows/ci.yml`.
2. Open **Actions** → **SENG363 Week 9 CI-CD** → **Run workflow**, or push a commit.
3. Open the workflow run to view Build, Test and Deploy logs.
4. Under Artifacts download `calculator-app` if needed.

Local test: `bash scripts/build.sh && bash scripts/test.sh && bash scripts/deploy.sh development`.

Note: Deploy is to a temporary directory on the GitHub runner, not to a hosted production service.
