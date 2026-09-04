# Design

An Excalibur is a world. Excalibur Moons arranges several complete Excaliburs
in a shared orbit: the Planet, the home moon nearest it, and every other Moon
gathered around them. The worlds can cooperate without giving up custody of
themselves.

## Authority

The summoner has final authority over the orbit and may operate its machines,
provider accounts, and recovery systems directly. No runtime service takes the
summoner's place.

The Planet is the summoner-controlled root on the main machine. It is not an
Excalibur world, a spirit, or an autonomous source of authority. It acts only
through powers the summoner has granted.

Every Moon has one declared administrative relationship with the Planet. The
declaration names every ordinary and recovery path. A local implementation may
realize those paths through provider controls, host administration, or a
bounded Planet service. Every administrative credential is scoped to one Moon
and unavailable to any resident spirit. A Moon receives neither a Planet
credential nor a path for initiating administrative access toward the Planet.

Keep these forms of authority and movement separate:

- the summoner and any delegated operators;
- the Planet's administration of a Moon;
- the home spirit's resident authority;
- another spirit's resident authority;
- entrances through which people visit a Moon;
- Moonlink correspondence;
- application-specific movement of data.

A key to one path opens none of the others.

## The home moon

One Moon is designated the home moon. It is the world nearest the Planet and
normally lives on the main machine beneath the Planet's root boundary. In a
provider-hosted orbit, it may instead be the first and most trusted virtual
machine reached by the Planet.

The home moon houses the primary generalist spirit. The summoner may give that
spirit a broader reviewed profile than other residents:

- stronger or more expensive model access;
- greater reasoning, charge, concurrency, or working budgets;
- more general spellbooks and mediated network access;
- wider writable authority inside its own realm;
- visibility into the health of the orbit and its declared Moonlinks;
- authority to petition every Moon through its declared Moonlink.

Every grant remains exact. Home status confers neither root nor Planet
credentials, provider control, another Moon's writable paths, or the power to
execute inside another Moon. The Planet administers the orbit; the home spirit
exercises judgment within its own Excalibur authority.

Other Moons often grow around a particular office, service, application, or
body of data. They are no less complete, and no less responsible for their own
realms. Home is a place in the orbit, not a rank over the other worlds.

## Isolation

The Planet may share the main machine with the home moon because the Planet is
the machine's root, not another Excalibur habitation. Every other Moon occupies
another virtual or physical machine. No machine houses two Moons.

A process, container, source tree, staged render, or provider session inside
another world may help prepare a Moon, but it is not one.

Every Moon has its own:

- machine identity and failure boundary;
- resident spirit and local offices;
- summoner-reviewed core and authority;
- realm, memory, practices, and application data;
- runtime and conversation custody;
- secrets and provider access;
- supervision, health, backup, recovery, and removal path.

A prepared machine without an enrolled resident spirit is a candidate. It may
prove installation and security behavior, but it cannot yet claim membership,
memory, audiences, credentials, or Moonlink authorship.

## Provider boundary

Let a provider do what it is structurally best placed to do:

- authenticate people at the edge;
- provide private ingress and publish services;
- carry traffic between machines;
- create hosts, handle images, bill the summoner, and operate the account;
- mediate model access or secrets.

There is no virtue in rebuilding these facilities merely to make every machine
look alike. A provider-managed model gateway that leaves no credential on a
Moon is preferable to a perfect local credential ceremony.

Keep locally what makes a Moon itself:

- resident identity and authority;
- realm, memory, practices, and conversations selected for retention;
- Moonlink meaning, admission decisions, and durable correspondence;
- application data and local audit evidence;
- enough portable release and recovery material to leave the provider.

Provider identity can authenticate a carrier. It does not define the meaning
of a payload or grant authority to its recipient. Add application
authentication when the provider's assertion is insufficient or when
correspondence must remain verifiable after moving elsewhere.

## Network and secrets

Private authenticated ingress is the ordinary posture. Any public exposure is
a separate decision with a named audience, authentication, limits, logging,
custodian, review date, and immediate path to revocation.

Bind application services locally when a provider or private network can
publish them without a routable listener. Inspect the provider's actual
forwarding behavior: loopback is not a trust boundary when a provider agent can
reach it.

No Moon receives a provider, mesh, shell, or administrative credential that
permits new access toward the Planet. Established response traffic may return
along a connection initiated by the Planet.

Prefer model access that leaves no bearer credential on a Moon. When a Moon
must hold one, scope it to that Moon and the narrowest practical service
identity. Never reuse it across Moons, expose it to a resident prompt, return
it to the Planet, or record it in source, declarations, receipts, or logs.

## Entrances

Excalibur defines spirit, shell, file, and optional voice entrances. The
summoner declares who may use each entrance to a Moon and what that entrance
reveals. Membership in the orbit and access to Moonlink open no entrance by
themselves.

The summoner or a delegated operator may hold root local to a Moon. Resident
spirits and ordinary services remain non-root. Local root grants no authority
over another Moon, the provider account, the Planet, or the network control
plane.

Route names, terminal software, web interfaces, and supervisors belong to the
local implementation rather than the law of the orbit.

## Declaration and observation

The Planet keeps a readable registry of Moon identity, custody,
administrative paths, communication paths, exposure, services, health checks,
resident capabilities, model access, backup posture, and unresolved attention.

The registry records policy and inventory; it is not a complete image of each
world. A Moon may develop locally. Before an update, observe that living state
and either preserve it, incorporate it into reviewed source, or stop when the
two cannot yet be reconciled. A legitimate local change is not drift to erase.

Running state is the source of truth for what is running. A declaration is the
source of truth for what is allowed. A discrepancy asks for attention; it does
not grant permission to overwrite either side.

Do not ask one label to carry several meanings:

- **intent** is illustrative or proposed;
- **approval** names a decision by the summoner and its scope;
- **evidence** is a dated observation or an exercised test;
- **lifecycle** is candidate, enrolled, suspended, or retired;
- **unknowns** remain explicit and block only the acts they affect.

“Live” is never a timeless property of a file. It is an observation with a
source and time.
