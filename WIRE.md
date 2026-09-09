# WIRE
Gemini chat cannot hold GitHub credentials. Correct.

Do not make a PAT. Do not make a GitHub App.

One secret on this repo:
Settings → Secrets and variables → Actions → New repository secret
Name: GEMINI_API_KEY
Value: key from Google AI Studio

Then: Actions → gemini-cold → Run workflow.
GITHUB_TOKEN already writes LOG.md on this repo.
