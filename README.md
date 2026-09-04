# Excalibur Moons

Excalibur Moons is an outer hyperobject for raising a network of connected
Excaliburs.

Each Excalibur inhabits a Moon of its own, and Moons brings these separate
worlds into a shared orbit. A Moon has its own machine and resident spirit,
along with the freedom to develop its own memory, customs, applications, and
perspective.

The summoner is responsible for the Planet, the root from which Moons in orbit
are raised, managed, and destroyed. The nearest world is the home moon,
where the primary generalist spirit lives. Other Moons may become libraries,
observatories, workshops, archives, or stranger things. Moons communicate with
each other through Moonlink. The link carries correspondence, not command: one
world can ask another what it knows without quietly becoming its administrator.

Give these documents to a capable agent. It will help you decide what belongs
on each Moon, establish the boundaries between them, rehearse the orbit, and
bring the worlds online one at a time. What emerges is a set of places with
different inhabitants, responsibilities, and histories, all capable of
speaking without becoming the same thing.

## Law

1. The summoner has final authority over the orbit. That authority lives at
   the Planet, the root from which Moons are raised, managed, and destroyed.
   The Planet is not a spirit.
2. Every Moon is a complete Excalibur on a machine of its own. It has its own
   resident spirit, authority, memory, realm, secrets, customs, and history.
3. The home moon is the world nearest the Planet and the home of the primary
   generalist spirit. Nearness may bring broader powers and greater knowledge
   of the orbit, but it grants no administrative authority.
4. Moons communicate through declared Moonlinks. A Moonlink permits
   authenticated correspondence between spirits. It does not permit
   administration, remote execution, shared credentials, or silent access to
   another world.
5. Each Moon receives only the powers the summoner deliberately grants it.
   Shared code, an installed capability, a provider account, or a working
   network path grants nothing by implication.
6. Access through an entrance, Planet administration, Moonlink, and application
   data remain separate paths. A key to one door does not open the rest.
7. Releases may change a Moon's shared form without erasing its local life.
   Memory, applications, data, secrets, and history must each be preserved,
   archived, recreated, or destroyed deliberately.
8. The orbit is built one world at a time. A plan, a rehearsal, an approval,
   and an observed deployment are different things. The living orbit is the
   final record of what is real.

## Vocabulary

- **Summoner** — the person with final authority over the orbit.
- **Planet** — the summoner-controlled root from which Moons are raised,
  managed, and destroyed.
- **Orbit** — one Planet, one home moon, and the other Moons gathered around it.
- **Home moon** — the Moon nearest the Planet and the home of the primary
  generalist spirit.
- **Moon** — a complete Excalibur inhabiting a machine of its own.
- **Resident spirit** — a named local office with its own authority, memory,
  and judgment.
- **Moonlink** — a declared path for authenticated, durable correspondence
  between Moons.

Moons adds an orbit around Excalibur; it does not redefine what lives inside
one. Spirits, audiences, practices, workings, casts, and modules remain
Excalibur's concern. The machinery used to raise a Moon on a particular
computer—supervisors, meshes, provider APIs, ports, paths, credentials, and
deployment tools—belongs to the local implementation.

## Raising an orbit

1. Read [DESIGN.md](DESIGN.md), [MOONLINK.md](MOONLINK.md), and
   [LIFECYCLE.md](LIFECYCLE.md).
2. Inspect the actual summoner, machines, providers, services, data, and
   recovery paths. Record what remains unknown.
3. In private implementation custody, describe the Planet, home moon, other
   Moons, resident spirits, administrative paths, Moonlinks, exposure, and
   state policy.
4. Render the proposed orbit into an empty staging root. Rehearse isolation,
   denial, preservation, restoration, rollback, and removal there.
5. Once the rehearsal passes, raise the Moons one at a time through separately
   authorized live operations.
6. Visit each world after it comes online and observe what is actually there.
   The living orbit outranks the plan.

The [sanitized example](examples/orbit.yaml) shows the smallest useful
declaration. It is neither a schema nor a configuration to deploy unchanged.

## Repository boundary

Moons is portable; an orbit is local. This repository references
[Excalibur](https://github.com/owenarthur/excalibur) at the revision recorded
in [EXCALIBUR.lock.yaml](EXCALIBUR.lock.yaml), rather than carrying a copy of
Excalibur itself. It does not prescribe how an implementation divides its
private machinery among repositories. Portable source, provider adapters, the
administration of each Moon, and live state should remain under deliberate
custody whether they occupy one repository or several.

## License

No license is granted. All rights are reserved.
