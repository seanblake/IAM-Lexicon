Abbreviated as: [[CA]]

Synonymous with [[Certificate Authority]] (which is more commonly used today), but Certification Authority is the original term used in standards and other formal publications.

Defined as either:
- An organization which conducts the business of issuing digital certificates; or,
- The computer system within a [[Public Key Infrastructure]] which performs the issuance of a [[Digital Certificate]]

Certification Authorities bind public keys to the identity of entities (e.g. individuals, organizations, websites) to whom they issue digital certificates.  This includes the CA itself - i.e. a [[CA Certificate]] bound to the identity of the CA.

Trust of a Certification Authority implies that one may trust the holder of a certificate the CA has issued is rightly associated with the identity they are asserting.

Certification Authorities may form hierarchies, the base of which is called a [[Root Certification Authority]] or [[Root CA]].  Often, Root CAs issue certificates only to other CAs, which in-turn issue a certificate to an [[End entity]].

Also see:
- [[Issuing Certification Authority]]
- [[Policy Certification Authority]]