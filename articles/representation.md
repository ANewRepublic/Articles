# Representation

Every adult [citizen](citizenship.md) has 1 vote.

This vote applies to their local jurisdiction and every enclosing larger jurisdiction up to the national level.

An adult may delegate their vote to a representative of their choosing for a given jurisdiction.
They may revoke or change this delegation at any time.
A citizen's own vote is strictly private.
A delegate's vote made on behalf of a delegating voter will be visible to that delegating voter.

Delegation is not required.
A citizen may retain their voting power to directly influence any law.

## Technical implementation

Each citizen is in possession of a cryptographic certificate.
This certificate is used to vote or can delegate their voting power to a representative.

Voting and delegation is recorded on the governance blockchain.

How can we prevent the creation of any voting proof that can be validated by anyone other than the expressly intended party?
We'd like to avoid the ability to do this so that people why "buy votes" (illegally) cannot ask a voter to prove that they in fact voted a particular way.
