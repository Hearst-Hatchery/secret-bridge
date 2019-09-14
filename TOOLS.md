Many tools exist to search a Git repository for potentially sensitive information. Each of these may have different capabilities and use different detection methods.

Here is a curated list of the secret detection tools we've come across:

| Name                  | URL                                                            | Installs Pre-Commit Hook? | Supported by `watcher` | Description                                                                                                           |
|-----------------------|----------------------------------------------------------------|---------------------------|------------------------|-----------------------------------------------------------------------------------------------------------------------|
| detect-secrets        | https://github.com/Yelp/detect-secrets                         | ✅                        | ✅                     | An enterprise friendly way of detecting and preventing secrets in code.                                               |
| git-secrets           | https://github.com/awslabs/git-secrets/blob/master/git-secrets | ✅                        | ✅                     | Prevents you from committing secrets and credentials into git repositories                                            |
| truffleHog            | https://github.com/dxa4481/truffleHog                          |                           |                        | Searches through git repositories for high entropy strings and secrets, digging deep into commit history              |
| yar                   | https://github.com/Furduhlutur/yar                             |                           |                        | Yar is a tool for plunderin' organizations, users and/or repositories.                                                |
| repo-supervisor       | https://github.com/auth0/repo-supervisor                       |                           |                        | Scan your code for security misconfiguration, search for passwords and secrets. 🔍                                    |
| gitleaks              | https://github.com/zricethezav/gitleaks                        |                           |                        | Audit git repos for secrets 🔑                                                                                        |
| gitrob                | https://github.com/michenriksen/gitrob                         |                           |                        | Reconnaissance tool for GitHub organizations                                                                          |
| repo-security-scanner | https://github.com/UKHomeOffice/repo-security-scanner          |                           |                        | CLI tool that finds secrets accidentally committed to a git repo, eg passwords, private keys                          |
| GitGot                | https://github.com/BishopFox/GitGot                            |                           |                        | Semi-automated, feedback-driven tool to rapidly search through troves of public data on GitHub for sensitive secrets. |