Abbreviated as: [[Issuing CA]]

A [[Certification Authority]] which issues [[Digital Certificates]] to an [[End entity]].

[[Public Key Infrastructure]] best-practice is to maintain an [[Offline Root CA]] which only issues certificates to [[Certification Authorities]] - like an Issuing CA.

A combined Root-Issuing CA is sometimes deployed in low-security environments like labs and development/testing environments, but it strongly discouraged for production. (For more info on the security mechanisms an [[Offline Root CA]] provides, see that article.)