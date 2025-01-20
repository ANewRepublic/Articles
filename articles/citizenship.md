# Citizenship

Citizens are adults who live within the boundaries of the nation who have applied for and been awarded a citizenship certificate.

## Applying for citizenship

Applications for citizenship requires:

* Taking an oath to support the governance of the nation as it currently stands.
* Submitting a biological sample as required to prove identity in the event that their citizenship certificate is lost.

Citizenship applicants may incur a nominal fee.
Citizens that do not have an electronic means of receiving their cryptographic citizenship certificate will need to purchase a device.

## Renewing citizenship

Citizenship must be renewed every 5 years.
Renewal requires:

* Appearing in person and providing a biological sample again and/or providing proof of possession of their current citizenship certificate.
* Renewing their oath.

This provides confidence that voting power is in the hands of citizens who are living and willing to live within or at least periodically visit the nation.

Renewal will never incur a fee.

## Proof of citizenship

Each citizen is in possession of a cryptographic certificate.
This certificate may serve many purposes including, but not limited to:

1. Proof of identity
1. Proof of citizenship
1. Proof of adulthood
1. Voting and delegating votes

3rd parties may create web apps that can accept zero-knowledge proofs from this certificate, such that the citizen can prove any subset of the above at their choosing.
These web apps may for example use this to gate access to adult content, to ensure each adult has at most one vote or one account on a social networking site, etc.

## Loss of certificate

Loss of the certificate may be reported to government services.
With alternative proof of identity, the certificate on file may be revoked.

## Renouncing citizenship

A citizen may renounce their citizenship at a government service office that is equipped to authenticate the citizen via a biological proof and presentation of their certificate.

## Minors

Minors are "guest citizens" if at least one of their guardians are citizens.

## Technical elements

The biological sample collected should be used to produce inputs to a zero-knowledge proof and MUST be destroyed after this process.

The purpose of the ZK proof is to allow the person to later provide proof of matching identity in order to revoke and/or re-issue their citizenship certificate, without giving the government a readable catalog of all citizens.
