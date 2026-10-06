ubuntu@ubuntu:~$ docker run -e GITHUB_AUTH_TOKEN=$MY_TOKEN -it --rm ghcr.io/ossf/scorecard/v5:latest --repo=github.com/keycloak/keycloak --show-details
Starting (github.com/keycloak/keycloak) [Vulnerabilities]
Starting (github.com/keycloak/keycloak) [Signed-Releases]
Starting (github.com/keycloak/keycloak) [Pinned-Dependencies]
Starting (github.com/keycloak/keycloak) [Packaging]
Starting (github.com/keycloak/keycloak) [Fuzzing]
Starting (github.com/keycloak/keycloak) [Branch-Protection]
Starting (github.com/keycloak/keycloak) [Dependency-Update-Tool]
Starting (github.com/keycloak/keycloak) [License]
Starting (github.com/keycloak/keycloak) [Maintained]
Starting (github.com/keycloak/keycloak) [SAST]
Starting (github.com/keycloak/keycloak) [Binary-Artifacts]
Starting (github.com/keycloak/keycloak) [Token-Permissions]
Starting (github.com/keycloak/keycloak) [Security-Policy]
Starting (github.com/keycloak/keycloak) [CI-Tests]
Starting (github.com/keycloak/keycloak) [Code-Review]
Starting (github.com/keycloak/keycloak) [CII-Best-Practices]
Starting (github.com/keycloak/keycloak) [Contributors]
Starting (github.com/keycloak/keycloak) [Dangerous-Workflow]
Finished (github.com/keycloak/keycloak) [SAST]
Finished (github.com/keycloak/keycloak) [Binary-Artifacts]
Finished (github.com/keycloak/keycloak) [Token-Permissions]
Finished (github.com/keycloak/keycloak) [Security-Policy]
Finished (github.com/keycloak/keycloak) [CI-Tests]
Finished (github.com/keycloak/keycloak) [Code-Review]
Finished (github.com/keycloak/keycloak) [CII-Best-Practices]
Finished (github.com/keycloak/keycloak) [Contributors]
Finished (github.com/keycloak/keycloak) [Dangerous-Workflow]
Finished (github.com/keycloak/keycloak) [Vulnerabilities]
Finished (github.com/keycloak/keycloak) [Signed-Releases]
Finished (github.com/keycloak/keycloak) [Pinned-Dependencies]
Finished (github.com/keycloak/keycloak) [Packaging]
Finished (github.com/keycloak/keycloak) [Fuzzing]
Finished (github.com/keycloak/keycloak) [Branch-Protection]
Finished (github.com/keycloak/keycloak) [Dependency-Update-Tool]
Finished (github.com/keycloak/keycloak) [License]
Finished (github.com/keycloak/keycloak) [Maintained]

## RESULTS

Aggregate score: 8.7 / 10

Check scores:
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| SCORE | NAME | REASON | DETAILS | DOCUMENTATION / REMEDIATION |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Binary-Artifacts | no binaries found in the repo | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#binary-artifacts | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 8 / 10 | Branch-Protection | branch protection is not maximal on development and all release branches | Info: 'allow deletion' disabled on branch 'main' | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#branch-protection |
| | | | Info: 'force pushes' disabled on branch 'main' | |
| | | | Info: 'branch protection settings apply to administrators' is required to merge on branch 'main' | |
| | | | Warn: required approving review count is 1 on branch 'main' | |
| | | | Info: codeowner review is required on branch 'main' | |
| | | | Info: status check found to merge onto on branch 'main' | |
| | | | Info: PRs are required in order to make changes on branch 'main' | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | CI-Tests | 26 out of 26 merged PRs checked by a CI test -- score normalized to 10 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#ci-tests | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 5 / 10 | CII-Best-Practices | badge detected: Passing | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#cii-best-practices | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Code-Review | all changesets reviewed | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#code-review | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Contributors | project has 37 contributing companies or organizations | Info: found contributions from: IBM, OASIS-learn-study, PerfCake, PerfRepo, RUGSaar, WeblateOrg, aerogear, arquillian, asciidoctor, fabric8-launcher, fabric8-ui, forge, freeplane, gammu, gatein, hitachi ltd., ibm, identity tailor gmbh, infinispan, jboss-mobile, jgroups-extras, judcon, jugsaar, keycloak, kubeflow, openshiftio, osmandapp, phpmyadmin, picketbox, picketlink, red hat, redhat-developer, redhatofficial, sdaps, smart-home-bartOS, unknown-horizons, weblateorg | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#contributors |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Dangerous-Workflow | no dangerous workflow patterns detected | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dangerous-workflow | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Dependency-Update-Tool | update tool detected | Info: detected update tool: Dependabot: .github/dependabot.yml:1 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#dependency-update-tool |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Fuzzing | project is fuzzed | Info: OSSFuzz integration found | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#fuzzing |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | License | license file detected | Info: project has a license file: LICENSE.txt:0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#license |
| | | | Info: FSF or OSI recognized license: Apache License 2.0: LICENSE.txt:0 | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Maintained | 30 commit(s) and 7 issue activity found in the last 90 days -- score normalized to 10 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#maintained | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ? | Packaging | packaging workflow not detected | Warn: no GitHub/GitLab publishing workflow detected. | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#packaging |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 8 / 10 | Pinned-Dependencies | dependency not pinned by hash detected -- score normalized to 8 | Info: Possibly incomplete results: error parsing shell code: invalid parameter name: integration/client-cli/admin-cli/src/main/bin/kcadm.sh:0 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#pinned-dependencies |
| | | | Info: Possibly incomplete results: error parsing shell code: invalid parameter name: integration/client-cli/admin-cli/src/main/bin/kcreg.sh:0 | |
| | | | Warn: containerImage not pinned by hash: operator/Dockerfile:1 | |
| | | | Warn: containerImage not pinned by hash: operator/Dockerfile:6: pin your Docker image by updating registry.access.redhat.com/ubi9-micro to registry.access.redhat.com/ubi9-micro@sha256:7a0454cbd9bd847e8f6a63b6f0254a6efbeb6e0ed71a5d824a4f6cccbe626650 | |
| | | | Warn: containerImage not pinned by hash: operator/scripts/Dockerfile-custom-image:3 | |
| | | | Warn: containerImage not pinned by hash: quarkus/container/Dockerfile:1 | |
| | | | Warn: containerImage not pinned by hash: quarkus/container/Dockerfile:22: pin your Docker image by updating registry.access.redhat.com/ubi9-micro to registry.access.redhat.com/ubi9-micro@sha256:7a0454cbd9bd847e8f6a63b6f0254a6efbeb6e0ed71a5d824a4f6cccbe626650 | |
| | | | Warn: containerImage not pinned by hash: test-framework/db-edb/container/Dockerfile:1: pin your Docker image by updating registry.access.redhat.com/ubi9 to registry.access.redhat.com/ubi9@sha256:5858f9ace07316e3b12caab62f6c2481a5030bb6bafdca5a9ea324c321ef36df | |
| | | | Warn: downloadThenRun not pinned by hash: test-framework/db-edb/container/Dockerfile:12-15 | |
| | | | Warn: pipCommand not pinned by hash: .github/scripts/ansible/aws_ec2.sh:16 | |
| | | | Info: 130 out of 130 GitHub-owned GitHubAction dependencies pinned | |
| | | | Info: 12 out of 12 third-party GitHubAction dependencies pinned | |
| | | | Info: 0 out of 6 containerImage dependencies pinned | |
| | | | Info: 0 out of 1 downloadThenRun dependencies pinned | |
| | | | Info: 0 out of 1 pipCommand dependencies pinned | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 9 / 10 | SAST | SAST tool detected but not run on all commits | Info: SAST configuration detected: CodeQL | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#sast |
| | | | Info: SAST configuration detected: CodeQL | |
| | | | Info: SAST configuration detected: CodeQL | |
| | | | Info: SAST configuration detected: CodeQL | |
| | | | Warn: 25 commits out of 30 are checked with a SAST tool | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Security-Policy | security policy file detected | Info: security policy file detected: SECURITY.md:1 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#security-policy |
| | | | Info: Found linked content: SECURITY.md:1 | |
| | | | Info: Found disclosure, vulnerability, and/or timelines in security policy: SECURITY.md:1 | |
| | | | Info: Found text in security policy: SECURITY.md:1 | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 8 / 10 | Signed-Releases | 5 out of the last 5 releases have a total of 5 signed artifacts. | Info: signed release artifact: keycloak-999.0.0-SNAPSHOT.tar.gz.asc: https://github.com/keycloak/keycloak/releases/tag/nightly | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#signed-releases |
| | | | Info: signed release artifact: keycloak-26.8.0.tar.gz.asc: https://github.com/keycloak/keycloak/releases/tag/26.8.0 | |
| | | | Info: signed release artifact: keycloak-26.7.5.tar.gz.asc: https://github.com/keycloak/keycloak/releases/tag/26.7.5 | |
| | | | Info: signed release artifact: keycloak-26.7.4.tar.gz.asc: https://github.com/keycloak/keycloak/releases/tag/26.7.4 | |
| | | | Info: signed release artifact: keycloak-26.7.3.tar.gz.asc: https://github.com/keycloak/keycloak/releases/tag/26.7.3 | |
| | | | Warn: release artifact nightly does not have provenance: https://api.github.com/repos/keycloak/keycloak/releases/78213075 | |
| | | | Warn: release artifact 26.8.0 does not have provenance: https://api.github.com/repos/keycloak/keycloak/releases/400674757 | |
| | | | Warn: release artifact 26.7.5 does not have provenance: https://api.github.com/repos/keycloak/keycloak/releases/400263044 | |
| | | | Warn: release artifact 26.7.4 does not have provenance: https://api.github.com/repos/keycloak/keycloak/releases/389986222 | |
| | | | Warn: release artifact 26.7.3 does not have provenance: https://api.github.com/repos/keycloak/keycloak/releases/379623625 | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Token-Permissions | GitHub workflow tokens follow principle of least privilege | Info: jobLevel 'contents' permission set to 'read': .github/workflows/ci.yml:37 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#token-permissions |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/ci.yml:525 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/ci.yml:524 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/ci.yml:697 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/ci.yml:698 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/ci.yml:54 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/ci.yml:55 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/codeql-analysis.yml:39 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/codeql-analysis.yml:40 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/documentation.yml:36 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/documentation.yml:37 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/guides.yml:37 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/guides.yml:38 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/js-ci.yml:35 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/js-ci.yml:36 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/operator-ci.yml:38 | |
| | | | Info: jobLevel 'pull-requests' permission set to 'read': .github/workflows/operator-ci.yml:39 | |
| | | | Warn: jobLevel 'contents' permission set to 'write': .github/workflows/quarkus-next.yml:99 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/quarkus-next.yml:132 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/scan-dependencies.yml:46 | |
| | | | Info: jobLevel 'contents' permission set to 'read': .github/workflows/scan-dependencies.yml:106 | |
| | | | Info: jobLevel 'actions' permission set to 'read': .github/workflows/scan-dependencies.yml:107 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/schedule-nightly.yml:16 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/schedule-nightly.yml:32 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/stability-base.yml:57 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/stability-clustering.yml:53 | |
| | | | Warn: jobLevel 'actions' permission set to 'write': .github/workflows/stability-js-ci.yml:166 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/aurora-delete.yml:16 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/ci.yml:29 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/codeql-analysis.yml:27 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/conformance.yml:18 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/documentation.yml:26 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/guides.yml:26 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/js-ci.yml:26 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/js-wireit-cache.yml:21 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/label.yml:7 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/operator-ci.yml:28 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/quarkus-next.yml:18 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/scan-dependencies.yml:8 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/schedule-nightly.yml:9 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/stability-base-reruns.yml:23 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/stability-base.yml:14 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/stability-clustering.yml:14 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/stability-js-ci.yml:14 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/version-compatibility-matrix.yml:15 | |
| | | | Info: topLevel 'contents' permission set to 'read': .github/workflows/weblate.yml:26 | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10 | Vulnerabilities | 48 existing vulnerabilities detected | Warn: Project is vulnerable to: https://osv.dev/GHSA-794g-x443-36f7 | https://github.com/ossf/scorecard/blob/80ee3ecfedf8b19ab8991713a9fdb2e7dcd7262e/docs/checks.md#vulnerabilities |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-8hxp-qmph-w5gq | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-65r4-943x-97jj | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-4x5r-pxfx-6jf8 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-p498-v437-472g | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-w5vr-8v7q-w6rv | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-q58r-hwc8-rm9j | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-vxmc-5x29-h64v | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-3jxr-9vmj-r5cp | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-6j4f-fj2g-mc7p | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-mh99-v99m-4gvg | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-q2hr-2g5m-vwhr | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-qhr7-859c-m2p7 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-rgw5-rvv9-x895 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-f886-m6hf-6m8v | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-vfj7-8cjw-p6xm | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-73wf-gq98-2v4g | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-c83g-rgw3-j3cx | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-h39j-r5qq-r9mm | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-hrh2-vp3x-79xf | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-jwp9-9v96-94mx | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-mp2f-45pm-3cg9 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-g7r4-m6w7-qqqr | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-4c8g-83qw-93j6 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-7p8r-x3mc-p8w7 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-f65p-4m7j-42xc | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-fph4-wmhf-6fwf | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-hrr3-gc8f-f4qj | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-jqff-g426-hqxp | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-qw65-cvwx-89v3 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-v2hh-gcrm-f6hx | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-r4q5-vmmm-2653 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-2883-xcg3-v3hh | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-52cp-r559-cp3m | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-5p4m-2wfm-xmqj | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-h67p-54hq-rp68 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-28wg-ghj8-5hjv | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-2v37-7h3g-55p8 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-3v7f-55p6-f55p | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-c2c7-rcm5-vvqj | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-fxqj-rqcc-2cmp | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-r28c-9q8g-f849 | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-68fv-2mgg-jv7q | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-hp3w-g68c-fv3c | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-58qx-3vcg-4xpx | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-96hv-2xvq-fx4p | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-jgwc-jh89-rpgq | |
| | | | Warn: Project is vulnerable to: https://osv.dev/GHSA-j288-q9x7-2f5v | |
|---------|------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
