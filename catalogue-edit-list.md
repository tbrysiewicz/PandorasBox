# Running catalogue edit list

Updated 2026-11-05. These are pending catalogue edits and review findings; the records below have not been changed by this review.

1. **Stiefel complex count — correct the partial label.**
   - Family: `Beta/Problems/Families/stiefel-linear-sections/`.
   - Main Q1 record: `R_7697a26aafe67fbae7e6aac8bbb4e170bed51ab8c35af49e08b0a60b2bc98d11`.
   - Set `status: "solved"` and `answer.relation: "equal"`; state the full degree theorem, keeping the table as examples. Theorem 1.1 covers all n >= k, and Table 1 already covers the family's current n <= 4 domain.
   - Keep the stable-range record `R_ecbb7da096f4c97651764ced091b56ca272cb20316c5f3181423e71ca02ecf28` explicitly restricted to n >= 2k-1; do not describe that formula alone as covering the whole family.
   - Source: [Brysiewicz–Gesmundo, Theorem 1.1 and Table 1](https://arxiv.org/html/1909.10085v2).

2. **Rational cubics through eight points, exceptional locus — clarify what is complete.**
   - Q8 record: `R_a0746a690485ad54317e014d8c72eaa6505f794847bcb13fad105eae9132c7b8`.
   - Theorem 2.5 completely describes where the multiplicity-weighted irreducible count drops below 12: a collinear triple or six points on a conic. It does not by itself classify the whole non-unbranched locus asked for in `Questions/Q8/descriptor.md`.
   - Ramification, including cuspidal cubics, can reduce the number of distinct solutions without reducing this weighted count. Retain the distinction rather than automatically changing this Q8 record to solved.
   - Source: [Brysiewicz–Gesmundo–Steiner, Definition 2.2, Proposition 2.4, Theorem 2.5, and Table 1](https://arxiv.org/html/2309.07357v1).

3. **Nine tangent quadrics — distinguish historical attribution from modern proof.**
   - Q1 record: `R_e5595116abde6ff2cb8bf75f1b5452f3d527318cb4a0f46587730509f45e6d0a`.
   - Credit Schubert for the historical count and Brysiewicz–Fevola–Sturmfels for the modern derivation. Their paper proves the tangency-class identity and recovers the intersection numbers by a prime-ideal/multidegree computation, yielding 666841088.
   - Correct the source locator from “Proposition 2.2” to **Proposition 2.4, Theorem 3.1, and equation (1)**.
   - Source: [Tangent Quadrics in Real 3-Space](https://arxiv.org/html/2010.10879).

4. **Lines meeting four lines, exceptional locus — expand the scope before calling it solved.**
   - Q8 record: `R_e715eeb12d2d43bf18060eb4a5b6ad4e16e81b83cf2e2f632340bda799b98f7d`.
   - Current result treats only a chart: the first three lines are pairwise skew and the fourth is disjoint from them and not contained in their smooth quadric. On this chart the branch equation is `disc(Q|l4)=0`.
   - A complete Q8 answer must also cover configurations excluded from this chart, including positive-dimensional solution fibres. The current partial label describes limited coverage, not an unfinished proof of the chart statement.
   - Source to retain: [Leykin–Sottile, Section 1 and Figure 1](https://arxiv.org/pdf/0710.4607v4).

5. **Stiefel Galois — record the general theorem as the source of inheritance.**
   - Q2 record: `R_6205e9849c4fb1688a0084d0295ff8a78ca31228370274bd65b154563133cfb9`.
   - For k < n, irreducibility plus the characteristic-zero sectional-monodromy theorem gives S_D for unrestricted general complementary linear sections, by Bertini reduction to a curve. Record that provenance as an inherited result once the general theorem has its own catalogue source record.
   - The present family includes k = n: St(n,n) = O(n) has two components. The S_D conclusion does not cover those entries. Split the cases explicitly rather than marking the whole family full symmetric.
   - Fixed k < n instances already inherit from this family Q2 record.
   - Sources: [Brysiewicz–Gesmundo, Section 2.4 and Lemma 2.4](https://arxiv.org/html/1909.10085v2); [Kadets, Proposition 1.1](https://arxiv.org/pdf/1809.07293v2).
