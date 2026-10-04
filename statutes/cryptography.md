# Cryptographic specification

This statute is enduring. It states the properties the current specification has to meet. It does not name an algorithm, a curve, or a vendor. Those belong in a published specification that can be replaced when the math breaks.

## The specification

The council publishes a proposed specification as text and as buildable source. It becomes the current specification when enacted as an amendment to this statute, and its hash is written to the governance record.

Any citizen can build the source and recompute a tally, an enrollment proof, and a commit binding. A tally citizens cannot recompute has no legal force.

The specification defines the finality depth of the governance record. After that depth, the record is the legal record. A later fork does not repeal a statute or change a tally. Disputes go to a court.

## Properties it has to meet

The specification fails, and a court sets the amendment aside, if it does not provide all of the following:

- uniqueness of enrollment without a readable catalog of persons, and destruction of the biological sample at the ceremony
- device-bound, non-exportable credentials
- zero-knowledge proofs of citizenship, adulthood, and uniqueness that are unlinkable across verifiers unless the citizen links them
- one voting weight per citizen, delegated or direct, with a direct vote overriding delegation on that proposal
- receipt-free ballots: the voter can detect that the last ballot was omitted, and cannot hand a third party a proof of how they voted
- the same property for a delegator's view of how their weight was cast, shown to the delegator for the delegate notice before a delegate's vote can bind
- public recomputation of the jurisdiction-wide tally
- secrecy of delegator lists, and secrecy of a private delegate's ballot
- publication of a delegate's total weight when, and only when, it crosses the public-delegate threshold, together with that delegate's ballot, and never the list of delegators
- commitments for tax payment, ownership, and entity principals, with opening only as the privacy article allows
- a sortition seed committed before the pool is closed
- threshold signature of the enacted commit id, with no single operator able to substitute a commit
- a finality rule

A failed renewal leaves the specification in force. Repealing it takes a grave ballot. Records already created stay verifiable under the specification that created them. The council introduces a renewal or a replacement at least 180 days before each sunset. New enrollment and new ballots wait if, and only if, no specification is in force.

## Agents and keys

A specification that allows a credential to be copied to an agent, or that allows a ballot proof to be re-verified by a stranger, does not meet this statute. Delegation is the only way another mind, human or machine, participates in a vote, and the delegate is a citizen who casts the ballot.
