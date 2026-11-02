# opnory/support — agent contract

This repository holds Opnory's public support and legal documents (support,
security, privacy, cloud terms, licensing notes). It is documentation only:
there is no code, no build, and nothing to deploy. GitHub renders it.

The authoritative license lives in `opnory/opnory`. Do not change legal
meaning in a PR that claims to be editorial. Legal changes need the operator's
explicit approval in the PR.

## Delivery (GitOps)

**Identity.** Agents act on GitHub as the `opnory-agent` GitHub App, never with the
operator's credentials. Hermes agent profiles load this automatically: `gh`
and `git` in an agent shell authenticate as the App. The App cannot approve
its own pull requests.

**Change path.**
1. Branch.
2. Push.
3. Open a PR (App-authored).
4. The required checks pass.
5. The operator approves.
6. Merge.

`main` is protected by the org ruleset `default-branch-two-party`:
- a PR with 1 approval is required, and the last push must be approved by
  someone other than its pusher;
- stale approvals are dismissed;
- force pushes and deletion are blocked;
- only org admins (the operator) can bypass it.

**Testing.** `ci` (job `check`) runs on every PR and on push to `main`. It
checks relative links offline with lychee (`lychee --offline '**/*.md'`) and
runs `git diff --check`. It is the required status check for `main`.

**Deployment.** None. Merging to `main` publishes the documents as GitHub
renders them. Rollback is a revert PR.
