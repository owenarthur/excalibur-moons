# Lifecycle

A Moon is raised through observed state and explicit authority, not by writing
its name in a manifest.

## States

- **candidate** — an isolated machine may be prepared and tested, but has no
  enrolled resident, live membership, inherited memory, or Moonlink authorship;
- **enrolled** — the summoner has approved the identity and boundaries, the
  resident is running, and the declared entrances and Moonlinks have been
  observed;
- **suspended** — live access or correspondence is deliberately closed while
  custody is retained;
- **retired** — membership and access are revoked, and retained data has a
  named custodian and disposition.

Source may propose a state. Only an authorized operation followed by
observation establishes it.

## State classes

Classify every state root before raising, migrating, updating, restoring,
rolling back, or retiring a Moon.

| Class | Treatment | Typical contents |
| --- | --- | --- |
| carry | preserve as current local meaning | realm, resident identity and authority records, cornerstone, practices, useful memory, application data |
| archive | retain read-only, outside the active administration | former core, old audiences, completed workings, historical receipts and logs |
| discard | remove after reconciliation | sessions, claims, leases, locks, sockets, caches, stale queues and provider-thread handles |
| recreate | derive, rotate, or authenticate again | reviewed software, supervision, network publication, indexes, current runtime, credentials, communication epochs, provider access |

The table is a beginning, not a substitute for inspection. A Moon may classify
a particular item differently when the summoner names the reason and its
effect on recovery. Resident identity and authority records are durable;
credentials and other secret material are normally issued or authenticated
again rather than copied. Pending work between Moons must be reconciled before
its queue is discarded.

No durable root may have two writable incarnations. A candidate and an
enrolled Moon never point at the same realm, runtime, database, or secret
store.

## Before raising a Moon

1. Inspect the machine, provider, users, services, listeners, data,
   credentials, costs, and current recovery path without changing them.
2. Resolve every unknown that affects authority, exposure, custody, spending,
   destructive behavior, or recovery.
3. Pin Excalibur, the portable distribution, modules, platform adapters, and
   output-changing tools by immutable revision or digest.
4. Render into a new empty root. The renderer writes no live path and performs
   no provider, supervisor, network, or enrollment action.
5. Start the candidate with a synthetic identity and empty durable state.
   Prove service confinement, entrance boundaries, resident non-root
   authority, denial behavior, restart, and deterministic re-render.
6. Rehearse migration from a read-only snapshot using the state classes above.
7. Exercise backup restoration into an empty target, rollback, Moonlink
   revocation, loss of Planet administration, loss of the home moon, and
   complete removal.
8. Obtain the summoner's separate approval for the exact acts that will touch
   the living orbit.

A successful rehearsal is evidence. It is not authority to raise the Moon.

## Raising and renewing a Moon

Raising a candidate or updating an enrolled Moon begins with observation.
Compare the living world with the reviewed release and declaration. Treat each
difference as local state to preserve, a source change to incorporate, an
explicit proposal to supersede, or a conflict that must be resolved first.

Promotion stops every writer affected by the change, snapshots the previous
release, moves only reviewed software and recreated state, verifies the new
world, and then changes ingress or Moonlink routing. Update other Moons before
the home moon, and the Planet last, whenever a mixed release could strand
correspondence.

Rollback restores the previous software and routes while retaining any new
realm changes, conversations, artifacts, or application data created after
promotion for reconciliation. Erasing new durable meaning to make a rollback
look clean is data loss.

After promotion, record what was actually observed: identities, processes,
listeners, routes, model path, authority, backup posture, health, and known
simplifications. A healthy service does not erase attention owed to a missing
firewall, shared credential, incomplete restoration proof, or other declared
gap.

## Backup and recovery

Backup is chosen separately for each Moon. Planet administration does not
imply Planet custody of every Moon's bulk data.

An enabled policy names its custodian, readers, scope, exclusions, destination,
encryption, schedule, retention, and restoration proof. Replaceable bulk data
may be omitted. A disposable Moon may declare no backup. A backup that has not
been restored into an empty target is not yet a recovery path.

Recovery reconstructs reviewed software from locks, restores only selected
state and resident identity records, re-establishes local credentials and
provider access, advances communication epochs where cloning is possible, and
verifies the Moon before reopening entrances or Moonlinks. It cannot
manufacture missing memory, authority, or evidence.

## Retirement

Retiring a Moon means:

1. closing new administration and Moonlink delivery;
2. reconciling or abandoning pending operations explicitly;
3. exporting, archiving, returning, or destroying data according to the
   summoner's decision;
4. revoking provider, model, network, secret, and spending grants;
5. disabling services and removing membership;
6. retaining only the agreed audit and recovery evidence;
7. proving that the retired Moon cannot rejoin and that unrelated Moons still
   operate.

Deleting the provider host comes last. It is not, by itself, a retirement plan.
