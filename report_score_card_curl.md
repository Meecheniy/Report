^Cubuntu@ubuntu:~docker run -e GITHUB_AUTH_TOKEN=$MY_TOKEN -it --rm ghcr.io/ossf/scorecard/v5:latest --repo=github.com/curl/curl --show-detailsls
Starting (github.com/curl/curl) [Packaging]
Starting (github.com/curl/curl) [Maintained]
Starting (github.com/curl/curl) [Token-Permissions]
Starting (github.com/curl/curl) [Binary-Artifacts]
Starting (github.com/curl/curl) [Contributors]
Starting (github.com/curl/curl) [CII-Best-Practices]
Starting (github.com/curl/curl) [Security-Policy]
Starting (github.com/curl/curl) [Vulnerabilities]
Starting (github.com/curl/curl) [License]
Starting (github.com/curl/curl) [SAST]
Starting (github.com/curl/curl) [Pinned-Dependencies]
Starting (github.com/curl/curl) [CI-Tests]
Starting (github.com/curl/curl) [Code-Review]
Starting (github.com/curl/curl) [Fuzzing]
Starting (github.com/curl/curl) [Signed-Releases]
Starting (github.com/curl/curl) [Branch-Protection]
Starting (github.com/curl/curl) [Dependency-Update-Tool]
Starting (github.com/curl/curl) [Dangerous-Workflow]
Finished (github.com/curl/curl) [CII-Best-Practices]
Finished (github.com/curl/curl) [Security-Policy]
Finished (github.com/curl/curl) [Vulnerabilities]
Finished (github.com/curl/curl) [License]
Finished (github.com/curl/curl) [SAST]
Finished (github.com/curl/curl) [Pinned-Dependencies]
Finished (github.com/curl/curl) [CI-Tests]
Finished (github.com/curl/curl) [Code-Review]
Finished (github.com/curl/curl) [Fuzzing]
Finished (github.com/curl/curl) [Signed-Releases]
Finished (github.com/curl/curl) [Branch-Protection]
Finished (github.com/curl/curl) [Dependency-Update-Tool]
Finished (github.com/curl/curl) [Dangerous-Workflow]
Finished (github.com/curl/curl) [Packaging]
Finished (github.com/curl/curl) [Maintained]
Finished (github.com/curl/curl) [Token-Permissions]
Finished (github.com/curl/curl) [Binary-Artifacts]
Finished (github.com/curl/curl) [Contributors]

## RESULTS

Aggregate score: 8.3 / 10

Check scores:
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| SCORE | NAME | REASON | DETAILS | DOCUMENTATION / REMEDIATION |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Binary-Artifacts | no binaries found in the repo | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#binary-artifacts | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 3 / 10 | Branch-Protection | branch protection is not maximal on development and all release branches | Info: 'allow deletion' disabled on branch 'master' | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#branch-protection |
| | | | Info: 'force pushes' disabled on branch 'master' | |
| | | | Warn: branch 'master' does not require approvers | |
| | | | Warn: codeowners review is not required on branch 'master' | |
| | | | Warn: no status checks found to merge onto branch 'master' | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | CI-Tests | no pull request found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#ci-tests | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | CII-Best-Practices | badge detected: Gold | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#cii-best-practices | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Code-Review | Found 0/30 approved changesets -- score normalized to 0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#code-review | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Contributors | project has 35 contributing companies or organizations | Info: found contributions from: Bumblebee-Project, Debian, GTFOArgs, GitHub-Stars, HTTPArchive, NEAT-project, Rockbox, c-ares, cloudflare, cpredef, csutils, curl, git, git-for-windows, gitgitgadget, harbour, head of @tkcert, ietf-wg-dprive, libssh2, logrotate, maven-nar, microsoft, mpv-player, msysgit, nghttp2, ngtcp2, openscanhub, phpseclib, pwr-Solaar, pycurl, quicwg, red hat, teamviewer, wireshark, wolfssl | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#contributors |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Dangerous-Workflow | no dangerous workflow patterns detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dangerous-workflow | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Dependency-Update-Tool | update tool detected | Info: detected update tool: Dependabot: .github/dependabot.yml:1 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dependency-update-tool |
| | | | Info: detected update tool: RenovateBot: .github/renovate.json:1 | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Fuzzing | project is fuzzed | Info: OSSFuzz integration found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#fuzzing |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 9 / 10 | License | license file detected | Info: project has a license file: COPYING:0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#license |
| | | | Warn: project license file does not contain an FSF or OSI license. | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Maintained | 30 commit(s) and 21 issue activity found in the last 90 days -- score normalized to 10 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#maintained | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Packaging | packaging workflow not detected | Warn: no GitHub/GitLab publishing workflow detected. | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#packaging |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 5 / 10 | Pinned-Dependencies | dependency not pinned by hash detected -- score normalized to 5 | Info: Possibly incomplete results: error parsing shell code: ternary operator missing ? before :: tests/ech_tests.sh:0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#pinned-dependencies |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checkdocs.yml:58: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checkdocs.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checkdocs.yml:115: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checkdocs.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:138: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:157: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:178: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:196: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:73: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/checksrc.yml:78: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/checksrc.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/codeql.yml:79: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/codeql.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/configure-vs-cmake.yml:93: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/configure-vs-cmake.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/configure-vs-cmake.yml:150: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/configure-vs-cmake.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/distcheck.yml:289: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/distcheck.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/http3-linux.yml:228: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/http3-linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/http3-linux.yml:592: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/http3-linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/http3-linux.yml:890: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/http3-linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/linux.yml:487: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/linux.yml:500: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/linux.yml:941: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/linux.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/macos.yml:412: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/macos.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/macos.yml:581: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/macos.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/macos.yml:665: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/macos.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/macos.yml:95: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/macos.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/non-native.yml:507: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/non-native.yml/master?enable=pin | |
| | | | Warn: third-party GitHubAction not pinned by hash: .github/workflows/windows.yml:818: update your workflow using https://app.stepsecurity.io/secureworkflow/curl/curl/windows.yml/master?enable=pin | |
| | | | Info: 104 out of 104 GitHub-owned GitHubAction dependencies pinned | |
| | | | Info: 7 out of 31 third-party GitHubAction dependencies pinned | |
| | | | Info: 1 out of 1 containerImage dependencies pinned | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | SAST | SAST tool detected: CodeQL | Info: SAST configuration detected: CodeQL | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#sast |
| | | | Info: SAST configuration detected: CodeQL | |
| | | | Warn: no pull requests merged into dev branch | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Security-Policy | security policy file detected | Info: security policy file detected: SECURITY.md:1 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#security-policy |
| | | | Info: Found linked content: SECURITY.md:1 | |
| | | | Info: Found disclosure, vulnerability, and/or timelines in security policy: SECURITY.md:1 | |
| | | | Info: Found text in security policy: SECURITY.md:1 | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 8 / 10 | Signed-Releases | 5 out of the last 5 releases have a total of 5 signed artifacts. | Info: signed release artifact: curl-8.22.0.tar.bz2.asc: https://github.com/curl/curl/releases/tag/curl-8_22_0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#signed-releases |
| | | | Info: signed release artifact: curl-8.21.0.tar.bz2.asc: https://github.com/curl/curl/releases/tag/curl-8_21_0 | |
| | | | Info: signed release artifact: curl-8.20.0.tar.bz2.asc: https://github.com/curl/curl/releases/tag/curl-8_20_0 | |
| | | | Info: signed release artifact: curl-8.19.0.tar.bz2.asc: https://github.com/curl/curl/releases/tag/curl-8_19_0 | |
| | | | Info: signed release artifact: curl-8.18.0.tar.bz2.asc: https://github.com/curl/curl/releases/tag/curl-8_18_0 | |
| | | | Warn: release artifact curl-8_22_0 does not have provenance: https://api.github.com/repos/curl/curl/releases/381006034 | |
| | | | Warn: release artifact curl-8_21_0 does not have provenance: https://api.github.com/repos/curl/curl/releases/343907436 | |
| | | | Warn: release artifact curl-8_20_0 does not have provenance: https://api.github.com/repos/curl/curl/releases/315028247 | |
| | | | Warn: release artifact curl-8_19_0 does not have provenance: https://api.github.com/repos/curl/curl/releases/295498074 | |
| | | | Warn: release artifact curl-8_18_0 does not have provenance: https://api.github.com/repos/curl/curl/releases/274727430 | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Token-Permissions | GitHub workflow tokens follow principle of least privilege | Warn: jobLevel 'statuses' permission set to 'write': .github/workflows/appveyor-status.yml:23 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#token-permissions |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/label.yml:30 | |
| | | | Info: found token with 'none' permissions: .github/workflows/appveyor-status.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/checkdocs.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/checksrc.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/checkurls.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/codeql.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/configure-vs-cmake.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/curl-for-win.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/distcheck.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/http3-linux.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/label.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/linux-old.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/linux.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/macos.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/non-native.yml:1 | |
| | | | Info: found token with 'none' permissions: .github/workflows/windows.yml:1 | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Vulnerabilities | 0 existing vulnerabilities detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#vulnerabilities | |
|---------|------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
