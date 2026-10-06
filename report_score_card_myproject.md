ubuntu@ubuntu:~$ docker run -e GITHUB_AUTH_TOKEN=$MY_TOKEN -it --rm ghcr.io/ossf/scorecard/v5:latest --repo=github.com/Meecheniy/laba_docker --show-details
Starting (github.com/Meecheniy/laba_docker) [CII-Best-Practices]
Starting (github.com/Meecheniy/laba_docker) [SAST]
Starting (github.com/Meecheniy/laba_docker) [Security-Policy]
Starting (github.com/Meecheniy/laba_docker) [Vulnerabilities]
Starting (github.com/Meecheniy/laba_docker) [Contributors]
Starting (github.com/Meecheniy/laba_docker) [CI-Tests]
Starting (github.com/Meecheniy/laba_docker) [Dangerous-Workflow]
Starting (github.com/Meecheniy/laba_docker) [Token-Permissions]
Starting (github.com/Meecheniy/laba_docker) [Binary-Artifacts]
Starting (github.com/Meecheniy/laba_docker) [Packaging]
Starting (github.com/Meecheniy/laba_docker) [Branch-Protection]
Starting (github.com/Meecheniy/laba_docker) [Fuzzing]
Starting (github.com/Meecheniy/laba_docker) [Dependency-Update-Tool]
Starting (github.com/Meecheniy/laba_docker) [Maintained]
Starting (github.com/Meecheniy/laba_docker) [Code-Review]
Starting (github.com/Meecheniy/laba_docker) [License]
Starting (github.com/Meecheniy/laba_docker) [Pinned-Dependencies]
Starting (github.com/Meecheniy/laba_docker) [Signed-Releases]
Finished (github.com/Meecheniy/laba_docker) [SAST]
Finished (github.com/Meecheniy/laba_docker) [Security-Policy]
Finished (github.com/Meecheniy/laba_docker) [Vulnerabilities]
Finished (github.com/Meecheniy/laba_docker) [Contributors]
Finished (github.com/Meecheniy/laba_docker) [CI-Tests]
Finished (github.com/Meecheniy/laba_docker) [Dangerous-Workflow]
Finished (github.com/Meecheniy/laba_docker) [Token-Permissions]
Finished (github.com/Meecheniy/laba_docker) [Binary-Artifacts]
Finished (github.com/Meecheniy/laba_docker) [Packaging]
Finished (github.com/Meecheniy/laba_docker) [Branch-Protection]
Finished (github.com/Meecheniy/laba_docker) [Fuzzing]
Finished (github.com/Meecheniy/laba_docker) [Dependency-Update-Tool]
Finished (github.com/Meecheniy/laba_docker) [Maintained]
Finished (github.com/Meecheniy/laba_docker) [Code-Review]
Finished (github.com/Meecheniy/laba_docker) [License]
Finished (github.com/Meecheniy/laba_docker) [Pinned-Dependencies]
Finished (github.com/Meecheniy/laba_docker) [Signed-Releases]
Finished (github.com/Meecheniy/laba_docker) [CII-Best-Practices]

## RESULTS

Aggregate score: 2.1 / 10

Check scores:
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| SCORE | NAME | REASON | DETAILS | DOCUMENTATION / REMEDIATION |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Binary-Artifacts | no binaries found in the repo | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#binary-artifacts | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Branch-Protection | branch protection not enabled on development/release branches | Warn: branch protection not enabled for branch 'main' | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#branch-protection |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | CI-Tests | no pull request found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#ci-tests | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | CII-Best-Practices | no effort to earn an OpenSSF best practices badge detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#cii-best-practices | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Code-Review | Found 0/2 approved changesets -- score normalized to 0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#code-review | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Contributors | project has 0 contributing companies or organizations -- score normalized to 0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#contributors | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Dangerous-Workflow | no workflows found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dangerous-workflow | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Dependency-Update-Tool | no update tool detected | Warn: no dependency update tool configurations found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dependency-update-tool |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Fuzzing | project is not fuzzed | Warn: no fuzzer integrations found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#fuzzing |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | License | license file not detected | Warn: project does not have a license file | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#license |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Maintained | 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#maintained | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Packaging | packaging workflow not detected | Warn: no GitHub/GitLab publishing workflow detected. | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#packaging |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Pinned-Dependencies | dependency not pinned by hash detected -- score normalized to 0 | Warn: containerImage not pinned by hash: Dockerfile:1: pin your Docker image by updating nginx:latest to nginx:latest@sha256:f9ea18bfa4fad859e1ed38259d711da7ccad2c3516e875cec3351a57c859f571 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#pinned-dependencies |
| | | | Info: 0 out of 1 containerImage dependencies pinned | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | SAST | no SAST tool detected | Warn: no pull requests merged into dev branch | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#sast |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Security-Policy | security policy file not detected | Warn: no security policy file detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#security-policy |
| | | | Warn: no security file to analyze | |
| | | | Warn: no security file to analyze | |
| | | | Warn: no security file to analyze | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Signed-Releases | no releases found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#signed-releases | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Token-Permissions | No tokens found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#token-permissions | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Vulnerabilities | 0 existing vulnerabilities detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#vulnerabilities | |
|---------|------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
