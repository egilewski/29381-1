29381
=====

Reproduction for [Renovate discussion](https://github.com/renovatebot/renovate/discussions/29381)

Context
=======

Dependabot created an alert in this repository for Pillow to be upgraded to v10.3.0 due to CVE-2024-28219.

Current behavior
================

"Configure Renovate" PR (https://github.com/egilewski/29381/pull/1) in "What to Expect" lists update to Pillow v10.3.0 not as a security update ("Update dependency Pillow to v10.3.0").

After Renovate is configured, the dashboard will not mark or treat that update as a security either: https://github.com/egilewski/renovate-updates-not-marked-as-security/issues/4

Expected behavior
=================

"Configure Renovate" PR should mark the update as a security one in the "Configure Renovate" PR and in the dashboard, as well as create a PR for it if the limit of open PRs is reached.
