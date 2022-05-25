The goal of this repo is to arrive at a minimal schema that can be used to express a "trust claim" or simple assertion about an entity, possibly including an object, and to demonstrate rollups and models using data in this form.

The claim must be signed by the issuer, but may be derived from a secondary source, ie seen on a web page or heard from another party.

The claim has two important dates, the issued date and the effective date - it is possible to claim on Tuesday that a car crashed on Monday.

The issuer may also be the subject of a claim, this is of key importance to establish credibility (or lack thereof).

A secondary goal is that the same schema may be used for any claim from the effectiveness of laundry detergent to a human rights violation, so that the format may be widely used, and that credibility in one area such as professional achievement may be used in another.

Note that the conclusions, if any, are decoupled from the claims.  Various types of graphs or models may be applied to the claims.

## Related works

[Trustgraph](https://github.com/trustgraph/trustgraph) a trust graph implemented over a trust atom format.  @harlantwood participated in the work leading to OpenTrustClaims schemas and code.

Alexander Cobleigh's TrustNet https://cblgh.org/articles/trustnet.html

Matrix sharable greylists https://github.com/matrix-org/matrix-doc/blob/msc2313/proposals/2313-moderation-policy-rooms.md and https://github.com/matrix-org/matrix-doc/pull/3215

[TechRFC1: Open Reputation Feed](https://docs.google.com/document/d/1DSHW8tEEWJrBXGtiwUjB5qTp6hxkFRWLKq_BJuzZkiE/edit#) an RFC specifically in the area of disinformation and human rights, for a trust claim format


