---
title: "Shorter, Tighter, FAESTer: Optimizations and Improved (QROM) Analysis for VOLE-in-the-Head Signatures"
collection: publications
category: conferences25
permalink: /publication/faest2
excerpt: 'In the past decade and largely in response to the NIST standardization effort for post-quantum cryptography, many new designs for digital signatures have been proposed. Among those, the FAEST digital signature scheme (Baum et al., CRYPTO 2023) stands out due to its interesting security-performance trade-off....'
date: 2025-08-17
venue: 'Advances in Cryptology - CRYPTO 2025, (Santa Barbara, CA, USA)'
paperurl: 'https://eprint.iacr.org/2026/164'
bibtexurl: 'https://dblp.org/rec/conf/crypto/BaumBBGKMMORRRS25.html?view=bibtex'
---
In the past decade and largely in response to the NIST standardization effort for post-quantum cryptography, many new designs for digital signatures have been proposed. Among those, the FAEST digital signature scheme (Baum et al., CRYPTO 2023) stands out due to its interesting security-performance trade-off. It only relies on  well-tested symmetric-key cryptographic primitives, as it constructs a digital signature from a zero-knowledge (ZK) proof of knowledge of an AES key. To achieve this, it uses the VOLE-in-the-Head ZK proof system which relies only on pseudorandom generator (PRG) and hash function calls. FAEST simultaneously has relatively small signature size and competitive sign and verify times.

In this work, we improve both the security and practical efficiency of FAEST. We improve the main computational  bottleneck of the original construction by replacing hash function calls in the underlying vector commitment scheme with calls to an AES-based PRG.  At the same time, we also improve the signature size by revisiting the evaluation of the AES block cipher in ZK. We use observations from Galois Theory to compress the size of the witness (and thus signature), due to the algebraic nature of the AES S-Box. We implemented our new construction, and our benchmarks show that its sign and verify times reduce up to  over the state-of-the-art while achieving the same security and smaller signatures.

Finally, we analyze our resulting signature scheme both in the  Quantum Random Oracle Model (QROM) and its classical analogue. To achieve concretely good security bounds, we devise a new classical proof for FAEST based on Renyi divergence techniques. We construct a QROM analogue and present a new Fiat-Shamir transform which is applicable to VOLE-in-the-Head-based signature schemes.
