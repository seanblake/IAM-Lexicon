A [[Certification Authority]] which digitally signs its own [[CA Certificate]].  

Participants in a [[Public Key Infrastructure]] trust the [[Root CA]] explicitly, facilitating implicit trust of:
- Any [[Certification Authority]] whose [[CA Certificate]] is signed by the [[Root CA]] (the 2nd [[tier]] in a [[PKI]] hierarchy)
- Any [[Certification Authority]] whose [[CA Certificate]] is signed by another [[CA]] which is in the [[Chain of trust]] to the [[Root CA]] (the 3rd-to-nth [[tier]] in a PKI hierarchy)
- Any [End Entity] in the [[Chain of trust]] to the [[Root CA]]

