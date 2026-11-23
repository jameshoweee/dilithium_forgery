# Exploiting Determinism in Lattice-based Signatures: Practical Fault Attacks on pqm4 Implementations of NIST Candidates

Source code for the forgery attack on the Dilithium signature scheme [1], a lattice-based candidate in the NIST post-quantum cryptography (PQC) standardisation process [2]. The results are reported in [3], presented at the 14th ACM Asia Conference on Computer and Communications Security (AsiaCCS 2019) in Auckland, New Zealand, 7 to 12 July 2019.

## Build

```
make
```

This builds `PQCgenKAT_sign`, `test/test_vectors` and `test/test_dilithium`. The first two link against OpenSSL's `libcrypto`.

## References

[1] Vadim Lyubashevsky, Léo Ducas, Eike Kiltz, Tancrède Lepoint, Peter Schwabe, Gregor Seiler, and Damien Stehlé. CRYSTALS-Dilithium. NIST PQC Round 1 submission, 2017. <https://csrc.nist.gov/projects/post-quantum-cryptography/round-1-submissions>

[2] NIST. Post-Quantum Cryptography Standardization. <https://csrc.nist.gov/projects/post-quantum-cryptography>

[3] Prasanna Ravi, Mahabir Prasad Jhanwar, James Howe, Anupam Chattopadhyay, and Shivam Bhasin. Exploiting Determinism in Lattice-based Signatures: Practical Fault Attacks on pqm4 Implementations of NIST Candidates. In Proceedings of the 2019 ACM Asia Conference on Computer and Communications Security (AsiaCCS 2019), pp. 427-440. ACM. <https://doi.org/10.1145/3321705.3329821>
