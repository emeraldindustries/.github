# Contributing to Emerald Industries (organization default)

Keep changes focused and follow the owning repository's engineering method, license, native-tooling requirements and security instructions. Repository-specific contracts govern their product and effect boundaries; they must not silently remove the owner-required source-custody minimum below.

## Commit and remotely preserve the actual work, including WIP

**No indispensable source only on a workstation. No remote collection, no completed source handoff. A WIP branch is visibility and custody, not canonical main or product acceptance.**

Before source work, identify its existing owning issue, source repository, authorized development branch, author, independent collector, scoped workspace and next collection checkpoint. Reuse suitable existing work and refs; do not create a duplicate task or one branch per correction.

At the next safe boundary of current work, checkpoint the actual publishable source. Then repeat after each coherent slice and before a material handback, independent review intake, planned idle, assignment change, successor/compaction handoff, or a long run depending on new local-only source. Preserve active one-writer/atomic-operation boundaries. **Do not wait for tests, review, a successful build, installation or feature completion to preserve WIP.** Label unfinished, failing, untested and REVISE checkpoints honestly.

1. Account for local HEAD/base/parents, staged and unstaged changes, deletions, renames and source-bearing untracked files. Include code, tests, fixtures, lockfiles and relevant build/documentation inputs. Preserve distinct index/worktree intent where material; do not discard another writer's changes, stashes or failed predecessors.
2. Commit the genuine current source and publish non-force to a durable development ref in the owning repository through the permitted route. A new WIP checkpoint is not a reconstruction of an unavailable historical commit. Do not mutate a frozen source/authorization ref for a preservation note.
3. Verify local scoped source against the remote checkpoint: HEAD, tree, ordered parents, changed paths/modes, required source closure and observation time. Account explicitly for remaining dirty/untracked source and later local edits. A successful push or matching branch name alone does not establish parity.
4. A separate collector retrieves the exact remote objects and changed source bodies, reconciles the author's source inventory, and checks required original evidence and referenced source inputs. Referenced dependency/submodule/LFS bytes require their own actual admitted custody; pointers alone are insufficient. Record the receiving result in the owning issue.
5. Record remote custody and the actual correctness status separately. `REMOTE_PRESERVED` may await independent collection; `PARITY_VERIFIED / SOURCE_COLLECTED` does not mean source correctness, main integration, native qualification, installation or release. Source delivery additionally requires the assignment's actual acceptance predicates.

**Parity is scoped and timestamped, not continuous workstation telemetry.** New local edits make the prior parity receipt historical. Independent remote readback is not direct observation of unseen local files. An author must supply an accurate local inventory and disclose any source-bearing exclusion; missing source is `PARITY_INCOMPLETE`, not an invisible exception.

## Safe scope and executable blocker resolution

Source mirroring is not a laptop dump. Do not blindly stage everything. Secrets, credentials, private keys, personal data, protected operational originals, runtime authority, compiler caches and disposable generated output are not ordinary source payloads. Retain required protected evidence in approved durable custody and use only permissible references. Do not expose private source in a public repository or silently sanitize a partial source snapshot while claiming complete parity.

Check actual push/create/PR automation, rules, CI effects, audience and authority before publication. A branch named WIP or test is not automatically no-CI or private. Existing permitted source-only publication does not require a new product-quality approval at every checkpoint; it never authorizes ungranted effects or bypasses a prior refusal.

For a real publication/retrieval barrier, preserve originals and record `PUBLICATION_BLOCKED` or `RETRIEVAL_BLOCKED`, exact cause, custodian and resolver. The planner must supply a concrete next custody/publication work unit in the same disposition: actual target, permitted immediate actions, reserved decision if any, acceptance and resumption step. Do not leave a team indefinitely idle under an unassigned 'planner-owned' blocker, nor accumulate indispensable dependent local-only work. Continue unrelated already-authorized work. No rerouting, encoding, force, credential expansion or disabled checks to evade a refusal.

Active source must be resident/readable on its engineering node and independently recoverable from admitted remote custody. An on-demand cloud placeholder, local bundle, screenshot, patch, unreferenced object or chat is not a remote source ref. This is not permission to hydrate protected data, move runtime authority or delete local originals.

## Required handback fields

Use the existing issue/receipt, not a parallel ledger:

`task | author | local checkpoint HEAD/tree/time | remote repo/ref/HEAD/parents | changed source paths/modes and exclusions | collector/receiving receipt | tests/review scope and actual state | evidence custody/retention | integration target | next consumer | branch disposition checkpoint`

For non-source work, record `NO_SOURCE_CHANGE`; no artificial commit. Superseded/rejected work retains its genuine original identity and disposition, not a false completed-product claim. Large or protected originals stay in approved custody with a safe index and recovery route; an expiring artifact cannot be their only archive.

## Temporary-branch consumption and retirement

At branch creation or next use, name the owning task, author, collector, exact head/base, purpose, delivery/consumer target, first-unintegrated time if known and a concrete disposition checkpoint. Reuse the ref through corrections; a new name/chat does not reset its age. Keep current entrypoints accurate.

At handoff/completion or the checkpoint, perform one disposition: **INTEGRATE**, **CONSUMED/SUPERSEDED/REJECTED with durable retention**, or **RETAIN_UNTIL** an exact dependency/hold and next check. Do not leave a consumed test branch indefinitely parked. Inactivity, product completion or a reader ACK alone never authorizes deletion.

The repository owner retires the exact temporary branch only after independent verification that:

1. Its current head is the reviewed final head; no active writer, open dependent PR, unresolved consumer, special retention hold, frozen authority or unique later WIP requires the ref.
2. Required source, original lineage and evidence remain independently recoverable from a different approved durable destination. Normal merge ancestry may suffice. A squash, cherry-pick or equal final tree alone does not preserve the original lineage. Never depend on an unreferenced SHA or expired artifact; use existing governed retention rather than an orphan archive ref per test.
3. The owning issue records actual integration/consumption, retained location, identity proof, independent reviewer and exact deletion authorization under applicable repository controls. Preexisting explicit retention directions require their own disposition; no blanket override.
4. After permitted normal deletion, the temporary ref is verified absent and retained source/history remains retrievable. Record the result and update links. A changed head invalidates the deletion decision. No automatic timer deletion, forced ref reset, recursive branch sweep or implicit local worktree/cache cleanup.

**Retirement after these conditions is required closeout, not optional indefinite retention.** Automatic branch deletion must not precede the checks. Source preservation itself grants no merge, CI, release or deletion effect. A failed retirement leaves an explicit pending obligation without erasing accepted engineering credit.

## Verification and security

Bind requirements to original observations and the implementation that consumes them. Reviewers inspect that correspondence, not merely consistency of summaries. Unobserved facts stay UNKNOWN; tests cannot invent host state. Reuse accepted evidence instead of replaying campaigns. Follow the owning repository's SECURITY.md and disclosure boundaries.

This governs author/collector behavior. Policy text and forms do not install local observers, automated closure interlocks, required checks or branch cleanup. Mechanical enforcement may be claimed only after repository-specific implementation, independent refusal tests and effective controls. Versioned canon amendments retain their proper review/adoption route.

## License

Unless the owning repository states otherwise, contributions are licensed under MIT. Existing repository licenses and contribution terms are unchanged.
