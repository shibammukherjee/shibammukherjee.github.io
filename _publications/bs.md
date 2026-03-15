---
title: "Concretely Efficient Blind Signatures Based on VOLE-in-the-Head Proofs and the MAYO Trapdoor"
collection: publications
category: conferences26
permalink: /publication/bs
excerpt: 'Blind signatures (Chaum, CRYPTO 82) are important building blocks in many privacy-preserving applications, such as anonymous credentials or e-cash schemes. Recent years saw a strong interest in building Blind signatures from post-quantum assumptions, primarily from lattices. While performance has improved, no construction has  reached practical efficiency...'
date: 2026-08-12
venue: 'Accepted at USENIX 2026 (Baltimore, USA)'
paperurl: 'https://eprint.iacr.org/2026/164'
bibtexurl: 'https://dblp.org/rec/journals/iacr/BaumBBMR26.html?view=bibtex'
---
Blind signatures (Chaum, CRYPTO 82) are important build-
ing blocks in many privacy-preserving applications, such as anonymous
credentials or e-cash schemes. Recent years saw a strong interest in build-
ing Blind signatures from post-quantum assumptions, primarily from
lattices. While performance has improved, no construction has reached
practical efficiency in terms of computation and communication. The
state of the art requires at least 20 KB size of communication for each
showing of a lattice-based Blind signature to a verifier, and more than
100 ms in prover time.
In this work, we propose an alternative direction with a plausibly post-
quantum Blind signature scheme called PoMFRIT. It builds on top of the
VOLE-in-the-head Zero-Knowledge proof system (Baum et al. CRYPTO
2023), which we combine with the MAYO digital signature scheme (Beul-
lens, SAC 2021). We implement multiple versions of PoMFRIT to demon-
strate security and performance trade-offs, and provide detailed bench-
marks of our constructions. Signature issuance requires 0.45 KB commu-
nication for Blind signatures of size 6.7 KB. Showing a Blind signature
can be done in < 76 ms even for a conservative construction with 128 bit
security. As a building block for our Blind signature scheme, we imple-
ment the first VOLE-in-the-head proof for hash functions in the SHA-3
family, which we consider of independent interest.
