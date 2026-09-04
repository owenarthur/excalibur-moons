# Excalibur Moons

Read `README.md`, `DESIGN.md`, `MOONLINK.md`, and `LIFECYCLE.md` completely
before proposing or changing an orbit.

This repository defines only the law added when more than one Excalibur world
shares an orbit. Do not restate Excalibur's single-world law or add a local
provider or household implementation here.

## Rules

- Begin with observed people, hosts, custody, services, and recovery paths.
  Keep proposals, tests, approvals, lifecycle state, and observations distinct.
- Name one summoner, one Planet, and one home moon. The Planet is the
  summoner-controlled root, not a spirit. The home moon houses the primary
  generalist spirit. Enumerate every administrative and recovery path; no Moon
  receives a return credential or ambient authority over the Planet.
- Give every Moon its own machine, resident spirit, realm, runtime, secret
  boundary, and failure boundary.
- Declare the home spirit's broader model, budget, spellbook, network, working,
  realm, and orbit-visibility grants exactly. Home status grants no root,
  provider control, or authority inside another Moon.
- Keep entrances, Planet administration, Moonlink, and application data
  movement separate. None grants another.
- Declare both endpoints of every path between Moons. Unknown identity, purpose,
  payload, version, direction, or authentication fails closed.
- Prefer provider mechanisms for ingress, identity, transport, account
  operations, and credential mediation when they reduce locally held secrets.
  Keep spirit identity, authority, memory, realm, and durable records portable.
- Classify state as carry, archive, discard, or recreate. Never preserve all
  runtime by default and never run two writable copies of one durable root.
- Keep examples synthetic. Never record private names, domains, addresses,
  paths, credentials, or live configuration here.
- Do not claim a deployment, backup, restore, revocation, or recovery path was
  tested unless it was exercised and the evidence is named.
- Planning and rendering grant no authority to enroll, raise, expose, spend,
  authenticate, revoke, destroy, or publish.

## Required design output

A private implementation must identify:

1. summoner, operators, Planet, home moon, other Moons, resident spirits, and
   custody boundaries;
2. exact Planet administrative paths and their allowed acts;
3. the home spirit's explicit generalist capability profile;
4. entrances and exposure for each Moon;
5. Moonlinks and any other data paths between Moons;
6. provider, model-access, secret, and spending posture;
7. state classification, backup, restore, rollback, and removal policy;
8. unresolved decisions and the separate approvals needed to make state live.

Reference this repository by exact revision. Do not vendor or paraphrase it
into an implementation as local law.
