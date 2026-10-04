# Representation

Every adult citizen with voting weight has one vote in each enclosing jurisdiction.

Delegation is optional. A citizen may vote directly on any proposal. The ordinary path, for a person who would rather be at home or at work, is to name a delegate and go live a life. Direct voting is always there when a proposal matters to that citizen.

There is no seat to win. A delegate holds weight only while delegators leave it there, and they can take it back before the ballot closes.

## Delegation

A citizen may name a delegate for a jurisdiction, and may name a different delegate for any subject. The subject of a proposal is the file it amends. A default delegate may cover every subject in that jurisdiction, with per-subject overrides.

A delegate is a citizen with voting weight in that same jurisdiction. A delegate may re-delegate. Chains longer than 8 are void. Cycles are void. The whole chain is visible to the original citizen and to no one else.

A direct vote on a proposal overrides delegation for that proposal only. The override does not cancel the delegation for later proposals.

The delegation in force at the close is the one that counts. A citizen may change or revoke it until the close.

A delegate who abstains abstains the weight then held, except weight overridden by a direct vote.

## When a delegate is unfaithful

A delegate who wants weight counted at the close casts the vote early enough that each delegator can see it for the delegate notice beforehand. A delegate vote cast later does not count. The same timing applies to a delegate's objection.

The delegator may, after seeing that vote and until the close, revoke the delegation or cast a direct vote. The direct vote replaces the delegate's choice for that person's weight. No reason is required, and none is published. If the delegator does nothing, the delegate's vote binds at the close.

A chain works the same way. The cast that will be counted is visible to every person whose weight it carries, for one delegate notice, not one notice per link. Any of them can break the chain before the close.

Parties and associations are lawful. They are not offices and they cast no vote. Weight is delegated to a citizen, not to an organization.

## What is secret, and what a delegator can see

A citizen's own vote is secret. Whether a citizen voted directly, abstained, or delegated, and to whom, is secret.

A delegator can see how the delegate cast the delegator's weight. That view convinces the delegator. It is not a proof that convinces a buyer, an employer, a spouse, an officer, or a crowd.

A citizen can confirm that the citizen's own last ballot was counted, and cannot produce a confirmation that convinces anyone else.

These are the properties that make vote-buying fail. The cryptographic specification meets them. The constitution does not freeze a named algorithm.

The practical rules that support the properties:

- A citizen may replace a ballot until the close. Only the last ballot counts. A person who was watched once may vote again later.
- The credential cannot be exported or handed to an agent.
- Enrollment offices keep a private terminal. A person casts or recasts there with no observer from outside. Interfering with that terminal, or demanding to watch it, is coercion of a vote.
- Tallies published to the world show jurisdiction-wide totals. They do not show how a private delegate voted, and they do not list delegators.

Perfection against a coercer who can watch a person for the entire voting window is not claimed. The private terminal and the right to recast are the required mitigations. The crime of buying, selling, or coercing a vote or a delegation is in the criminal statute.

## Public delegates

A delegate who crosses the public-delegate threshold becomes a public delegate for that proposal. The total weight is what becomes public. The names behind it do not. For that proposal:

- the delegate's yes, no, or abstention is public
- the total weight the delegate casts is public
- the list of who delegated remains secret
- before the close, the delegate publishes financial interests and every payment received for public activity

A public delegate is paid only through an open channel funded by delegators, and publishes the total. Any other payment for the delegate's voting is a corrupt payment. There is no treasury salary, pension, or campaign fund for a delegate. There is no immunity.

A delegate below the threshold publishes none of this. Secrecy of small delegations is what stops a local boss from demanding proof of loyalty.

While a citizen serves on the council, as a judge, or as the prosecutor, delegations to that citizen are suspended and return to the delegators.

## The governance record

The governance record stores:

- commitments to credentials issued, renewed, replaced, and ended
- commitments to delegations
- ballot commitments and the public tally
- the commit id of the staging branch and of the enforced branch
- commitments to legal entities and their principals
- tax-payment proofs and liens, by parcel
- parcel geometry and assessment inputs
- the hash of the current cryptographic specification
- sortition seeds and the identities of people currently holding an office of force
- hashes of judgments, each citing the enacted text the judgment applied, so a later reader can see whether that enactment is still current

Office-holders who wield force are publicly known. Everyone else is a commitment. The record is public and any citizen can audit it. Operators of the ledger do not add a ballot, drop a ballot, or enact a law. After the specification's finality rule, a fork does not undo a tally or a commit id. A dispute about a record goes to a court.

## Advice is not a vote

A hosted forum may charge a small payment to rank a comment or a non-binding preference. The payment is unlinkable to the credential and to any ballot. One citizen, one preference on a given comment, proved in zero knowledge. Those preferences measure attention. They never enact, repeal, or interpret law.
