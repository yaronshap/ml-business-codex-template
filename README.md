# Machine Learning for Business Analytics — Codex Exercise

This repository is a starter project for a browser-based GitHub Codespaces assignment.

## Getting started

1. Create your own **private** GitHub repository using the instructor's template.
2. In your new repository, select **Code > Codespaces > Create codespace on main**.
3. Wait until setup finishes in the browser-based VS Code terminal.
4. Check the environment:
   ```bash
   codex --version
   .venv/bin/python starter.py
   ```
5. Sign in to Codex:
   ```bash
   codex login --device-auth
   ```
   Open the displayed login link in your own browser, and enter the code. If device authentication is disabled for your account, contact the instructor.
6. Start Codex:
   ```bash
   codex
   ```
7. Ask Codex to add a random forest classifier, compare its test accuracy with logistic regression, and explain the results. Review the code and rerun your experiment.
8. Commit and push your changes:
   ```bash
   git add starter.py README.md
   git commit -m "Compare logistic regression and random forest"
   git push
   ```
9. Verify the changes appear in your GitHub repository, then submit its URL.

## Notes

- Codex runs in your remote Codespace, not on your personal laptop.
- The synthetic dataset does not contain real customer information.
- Never put access tokens, passwords, or API keys into your Git repository.
- Stop your Codespace when finished to conserve compute hours.
