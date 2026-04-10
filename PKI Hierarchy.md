The concept of multiple [[Certification Authorities]] forming a hierarchical [[Chain of trust]] between a [[Root CA]], and any number of "[[Intermediate]]" [[Certification Authorities]] down to the level where an [[End entity certificate]] is issued.

The levels of [[Certification Authorities]] are referred to as a "[[Tier]]".  A [[PKI]] with a single [[Root CA]] which issues [[End entity certificate]] is referred to as "One-tier" or "Single-tier", due to a single [[CA]] in the [[Chain of trust]].  The naming convention continues as N-tier, where N refers to the number of [[Certification Authorities]].

Two-tier [[PKI]] are common for their balance of security (due to an [[Offline Root CA]]) and operational practicality.

Example diagram of a two-tier [[PKI]]:

	  +-----------------+
      |   Root CA       |
      |   (Offline)     |
      +-----------------+
             |
             v
      +-----------------+
      |   Issuing CA    |
      |   (Online)      |
      +-----------------+
             |
             v
      +-----------------+
      |   End Entities  |
      | (Users, Servers)|
      +-----------------+