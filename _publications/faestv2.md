---
title: "FAEST v2: Algorithm Specifications"
collection: publications
category: misc25
permalink: /publication/faestv2
excerpt: 'This document describes and specifies version 2 of the FAEST digital signature algorithm. It presents the underlying cryptographic components and specifies the building blocks used to construct the FAEST algorithm....'
date: 2025-02-10
venue: 'Technical report, National Institute of Standards and Technology'
paperurl: 'https://csrc.nist.gov/csrc/media/Projects/pqc-dig-sig/documents/round-2/spec-files/faest-spec-round2-web.pdf'
bibtexurl: ''
---
This document describes and specifies version 2 of the FAEST digital signature algorithm.
It presents the underlying cryptographic components and specifies the building blocks used
to construct the FAEST algorithm.
The design of FAEST is intended to provide security against attacks by quantum com-
puters by relying only on information-theoretic and symmetric-key cryptographic primi-
tives. In particular, in addition to the standard SHA3 hash function, the security of FAEST
is tightly linked to the security of AES128, AES192 and AES256, based on which the NIST
security categories 1, 3, and 5 are defined.
