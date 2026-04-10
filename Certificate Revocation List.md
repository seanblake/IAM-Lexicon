Abbreviated as [[CRL]]

A list of [[Digital Certificates]] maintained by the [[Certification Authority]] which issued them, which have been revoked.

Certificates may be revoked for a number of reasons ranging from no longer being required to known (or suspected) compromise of the certificate (i.e. an entity other than the subject has obtained the certificate's private key, allowing them to impersonate the subject.) 

Each entry on a CRL contains:
- A "reason code" describing why the certificate has been revoked; and,
- a serial number corresponding to the certificate

[[Relying Parties]] may refer to a [[CRL]] to check whether a certificate presented to it remains valid, as one step in the verification process. 

A [[CRL]] is generally published publicly for any participant in a [[PKI]] to query.  The locations they are published to are referred to as a [[Certificate Revocation List Distribution Point]]
