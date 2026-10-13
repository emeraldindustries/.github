# Contributing to Emerald Industries (organization default)

Keep changes focused and follow the owning repository's engineering method, license, native-tooling requirements and security instructions. Repository-specific contracts take precedence over generic tooling examples.

## Remote collection is a completion requirement

**No remote collection, no completed source handoff. No receiving issue, no orphaned work. No verified retrieval, no retirement of unique local work.**

Before source work, identify its existing owning issue, source repository and target branch, author, collecting reviewer, scoped workspace and next collection checkpoint. Do not create a second task or repair if accepted work already exists.

At each completed source slice and before a planned handoff/idle boundary:

1. Publish the allowed source checkpoint to its owning remote branch/PR through normal controls. A local commit or unreferenced remote object is not a collected branch.
2. Retrieve and verify the exact remote ref, commit, tree and changed files. Preserve original test/review evidence and its actual scope.
3. Make required evidence independently retrievable from approved durable custody; record locators, digests, access/retention and a recovery route. An expiring artifact cannot be the only retained evidence after expiry.
4. Have the collecting actor record the actual retrieval result in the existing issue. Only then mark the source handoff collected. Main integration, native/package/installed acceptance and release remain distinct.
5. Disposition remaining WIP and generated output. Keep unique source, Git/index/untracked work, required inputs and evidence. Local retirement and cache removal require their own actual clearance.

If publication or retrieval fails, preserve the work and record PUBLICATION_BLOCKED or RETRIEVAL_BLOCKED, its exact reason, custodian, resolver and next checkpoint. A checkpoint is a collect/extend/handoff decision, never an automatic deletion timer. Do not claim COMPLETE, silently abandon work or switch actors/transports to evade a refusal.

For non-source work, record NO_SOURCE_CHANGE with the actual outcome; no artificial commit. For superseded/rejected work, preserve original identity and name the genuine successor/disposition. Never disguise not-planned or superseded work as completed implementation.

## Required handback fields

Extend the existing repository receipt/issue rather than inventing a parallel schema: task URL; author and collector; source repo/ref/commit/tree; changed paths; original test/review scope; evidence locations/digests/access/retention; independent retrieval result/time; remaining WIP or explicit none; integration/retirement disposition; next consumer.

Source belongs in the owning repository. Current decisions and collection receipts belong in its established coordination issue/exchange. Large or protected evidence stays in approved custody, with a safe index; it is not automatically suitable for Git. Local paths and original chat memory are not a retrieval plan.

## Branch, PR, issue and entrypoint hygiene

Keep one owning task and one accountable collector. Every retained branch/PR has a current consumer or a recorded terminal disposition. Reconcile existing work before creating a new branch. Update current instructions in the same collected change, link original historical states immutably, and do not leave old launch instructions presented as current.

Close exhausted tasks only after the required receiving result; preserve original evidence. Source publication is not permission to merge, force-push, delete a branch, run CI, alter protected policy or retire a worktree. Do not mutate exact frozen execution refs for documentation. Retain valid sealed histories and consumed attempts.

## Verification and security

Bind requirements to actual original observations and the implementation that consumes them. The independent reviewer checks that correspondence, not just internal consistency of a summary. Unobserved facts stay UNKNOWN; tests cannot invent host state. Reuse accepted evidence instead of replaying costly campaigns.

Keep secrets, credentials, private keys, personal data and protected operational records out of unauthorized repositories/artifacts. Follow the repository's disclosure and access controls. The repository's SECURITY.md governs reporting. Do not broaden sharing to satisfy collection.

This document governs contributor and collector behavior. GitHub cannot see unpushed local work, and a checklist is not a claim of automatic closure enforcement. Required fields in the source-work form enforce form submission only; use actual collector verification before accepting completed source work.

## License

Unless the owning repository states otherwise, contributions are licensed under MIT. Existing repository licenses and contribution terms are unchanged.
