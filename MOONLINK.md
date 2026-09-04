# Moonlink

Moons communicate through Moonlink. In the topology described here, each
Moonlink joins the home spirit to the resident spirit of one other Moon and
carries durable correspondence between them. It is not administration, remote
execution, generic chat, file transfer, or a general network trust relationship.

This document describes direct links between the home moon and another Moon,
carried by a Planet-initiated network path declared for that purpose. A
different topology needs its own reviewed design. A Moonlink grants no
transitive access and no right to forward correspondence to a third Moon.

## Declaration

Before a Moonlink opens, both endpoints agree on:

- link id and protocol version;
- exact home-moon, Moon, and resident-spirit identities;
- permitted petition types and maximum size;
- authentication and integrity method;
- transport endpoint and allowed network initiator;
- admission of a new thread in each direction;
- whether replies on an admitted thread require another review;
- disclosure and consequential-action policy;
- retry, ordering, idempotency, queue, and acknowledgement behavior;
- retention, redaction, attention, and revocation policy.

If identity, version, direction, authentication, or declaration does not match,
the link remains closed. A declaration made by only one endpoint is inactive.

## Authorship and admission

Either resident spirit may author a petition. Authorship is distinct from
network initiation: a Moon that cannot open a connection toward the Planet can
place a local petition for collection over a Planet-initiated flow.

Authorship is also distinct from admission. Each direction declares whether a
new thread enters automatically or requires a decision from the summoner.
Admission belongs to one exact thread and records whether later replies and
corrections may continue without another decision.

Delivery establishes only that authenticated bytes arrived. It establishes
none of the following:

- permission to disclose additional material;
- acceptance of the request;
- approval of a consequential action;
- authority to execute anything on the recipient.

The receiving spirit applies its own local law. A petition may lead to an
ordinary audience or a bounded working, but its arrival invokes neither by
itself.

## Record

Every message names:

- link, thread, event, author, and recipient;
- protocol version and message type;
- creation and expiry time;
- body digest and disclosed-evidence references;
- predecessor or sequence information sufficient to detect gaps;
- acknowledgement and terminal outcome when applicable.

The durable chronicle records admission, disclosure, delivery, acceptance,
progress, result, failure, correction, cancellation, rescission, and
acknowledgement as append-only events. It preserves meaning and integrity, not
hidden reasoning or undeclared source material.

Authentication covers the endpoint identities, link, version, direction,
body, time, and replay identifier. Provider-authenticated transport may
contribute one signal, but it is insufficient when another principal can forge
the provider assertion or when the record must remain verifiable after leaving
the provider.

Retries are idempotent. Gaps pause ordered delivery. Queues remain bounded and
surface attention before refusing new work; they never silently discard old
correspondence. A stale projection identifies itself as stale.

## Boundary

A Moonlink opens one narrow door between two spirits. It gives neither
endpoint:

- root, shell, supervisor, provider, network-control, or Planet authority;
- a cast, arbitrary command, writable path, or generic payload;
- another Moon's credential, memory, transcript, realm, or application data;
- permission to address or forward to a third Moon.

An implementation may carry Moonlink through HTTPS, polling, provider peer
transport, a private mesh, or another authenticated medium. The carrier does
not widen the door.

## Revocation and failure

Either endpoint may close a Moonlink. Revocation advances a declared epoch or
equivalent key generation so old credentials and queued messages cannot
quietly rejoin. Pending messages are delivered, abandoned, exported, or
destroyed according to explicit policy.

Each endpoint retains only the chronicle and disclosed material permitted by
its retention policy. Loss of the Planet, carrier, or peer leaves local
identity, realm, memory, and unrelated Moon operation intact.
