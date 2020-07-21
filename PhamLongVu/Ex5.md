a) Does T1 necessarily satisfy C2? Explain.
Yes. According to  definition of subsumption.
Criteria Subsumption: A coverage criterion C1 subsumes C2 if and only if every test set that satisfies criterion C1 also satisfies C2.

* b) Does T2 necessarily satisfy C1? Explain.
No. There is no reason to expect test requirements generated by C1 to be satisfied by T2.

* c) If P contains a fault, and T2 reveals the fault, T1 does not necessarily also reveal the fault. Explain.
No. Subsumption is about criteria, not about test sets. In particular, there is no requirement that test set T2 be a subset of test set T1.
So, it could happen that T2 contains that one test that reveals the fault, and T1 doesn't.