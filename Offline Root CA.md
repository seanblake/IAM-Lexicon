A [[Root Certification Authority]] which only issues [[Digital Certificates]] to other [[Certification Authorities]], and is usually powered off except when:
- renewing its own [[CA Certificate]]
- issuing or renewing a [[CA Certificate]] for another [[CA]] in its [[PKI Hierarchy]]
- or publishing a [[Certificate Revocation List]]

Usually a Root CA is not connected to any computer network, or any network which one is connected to is completely disconnected (i.e. "air-gapped") from other networks, and unreachable outside of its physical location.

The physical and logical security measures to protect a [[Root CA]] should be high (since its compromise could lead to compromise of the entire [[PKI]], and keeping one offline increases its resistance to compromise.