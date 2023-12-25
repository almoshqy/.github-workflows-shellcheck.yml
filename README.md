# ShellCheck Analysis with GitHub Actions

This repository contains shell scripts and a GitHub Action workflow that uses [ShellCheck](https://www.shellcheck.net/) to perform static analysis on shell scripts, ensuring they adhere to best practices and standard conventions.

## Author

**Abdullah Almoshqy**

## GitHub Action - ShellCheck

The `.github/workflows/shellcheck.yml` file defines a GitHub Action that automatically runs ShellCheck on the shell scripts in this repository whenever changes are pushed.



Each time a commit is pushed to the repository, GitHub Actions activates the ShellCheck workflow, which scans the shell scripts for common errors and potential issues.



To use the shell scripts in this repository:

```bash
git clone https://github.com/almoshqy/.github-workflows-shellcheck.yml.git
cd .github-workflows-shellcheck.yml/scripts
bash some-script.sh
