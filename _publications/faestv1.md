---
title: "FAEST: algorithm specifications"
collection: publications
category: misc23
permalink: /publication/faestv1
excerpt: 'This document describes and specifies the FAEST digital signature algorithm. It presents the underlying cryptographic components and specifies the building blocks used to construct the FAEST algorithm.....'
date: 2023-07-04
venue: 'Technical report, National Institute of Standards and Technology'
paperurl: 'https://csrc.nist.gov/csrc/media/Projects/pqc-dig-sig/documents/round-1/spec-files/FAEST-spec-web.pdf'
bibtexurl: ''
---
This document describes and specifies the FAEST digital signature algorithm. It
presents the underlying cryptographic components and specifies the building blocks
used to construct the FAEST algorithm.
The design of FAEST is intended to provide security against attacks by quan-
tum computers by relying only on information-theoretic and symmetric-key cryp-
tographic primitives. In particular, in addition to standard PRFs and PRGs for
randomness derivation, the security of FAEST is tightly linked to the security of
AES128, AES192 and AES256, based on which the NIST security categories 1, 3,
and 5 are defined.
