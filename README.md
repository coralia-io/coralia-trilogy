# Coralia Trilogy

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18121786.svg)](https://doi.org/10.5281/zenodo.18121786)

## What is this?

A mathematically defined set of integers with unusual structural properties, plus code to reproduce and test those properties.

```
C = {0, 1, 2, 3, 5, 7, 9, 12, 15, 23, 30, 35}
```

## Why does it exist?

It began as a pure math question: *Is there a unique 12-element subset of {0,...,35} satisfying certain structural constraints?*

Yes. Paper 1 proves it.

Paper 2 shows the axioms have predictive content: they predict where certain mathematical constants land when rounded to integers.

## What can I do with it in 5 minutes?

```bash
git clone https://github.com/coralia-io/coralia-trilogy.git
cd coralia-trilogy
python examples/landing_demo.py
```

Output:
```
Where do these land?

  e² = 7.39 → lands on 7 ∈ C
  e^π = 23.14 → lands on 23 ∈ C
  φ⁵ = 11.09 → lands on 11 ∈ not C
```

## Where do I go next?

| I want... | Go to... |
|-----------|----------|
| The math | `core/papers/` |
| Simple experiments | `examples/` |
| Domain applications | `sandbox/` |
| Reusable code | `interfaces/` |
| To know if this is for me | [WHO_THIS_IS_FOR.md](WHO_THIS_IS_FOR.md) |

---

## Structure

| Directory | Status | Contents |
|-----------|--------|----------|
| `core/` | Authoritative | Library, papers, proofs, tests |
| `interfaces/` | Reusable | Grammars, classifiers, exports |
| `sandbox/` | Exploratory | Domain applications |
| `examples/` | Entry point | Simple demos |

See [SCOPE.md](SCOPE.md)

---

## Papers

Three separate publications by **Emma Cecile**, [ORCID 0009-0008-4120-9309](https://orcid.org/0009-0008-4120-9309):

1. **The Coralia Sequence: A Unique Finite Integer Set Under Fibonacci-Lucas Terminal Constraints** (version 1.1, 2026-01-02). [DOI](https://doi.org/10.5281/zenodo.18121786) · [PDF](https://zenodo.org/records/18121786/files/coralia-sequence_math_v1.1.pdf).
2. **Axioms That Predict What They Don't Mention: Empirical Content of the Coralia Constraints** (version 1.0, 2026-01-05). [DOI](https://doi.org/10.5281/zenodo.18150002) · [PDF](https://zenodo.org/records/18150002/files/Axioms%20That%20Predict%20What%20They%20Don%E2%80%99t%20Mention.pdf).
3. **Aperture: The Geometry of Coralia** (version 1.0, 2026-01-23). [DOI](https://doi.org/10.5281/zenodo.18346226) · [PDF](https://zenodo.org/records/18346226/files/Cecile_2026_Aperture.pdf).

Paper I’s concept DOI, `10.5281/zenodo.18121785`, covers its versions; `10.5281/zenodo.18121786` identifies version 1.1. Both are valid. Paper III’s record also includes copies of the earlier papers; cite each paper with its own DOI.

Paper II’s canonical title follows its deposited PDF. Its DOI record previously used *Why These Axioms? Empirical Content of the Coralia Constraint*; both titles identify DOI `10.5281/zenodo.18150002`. The registered record correction remains pending.

[Read the papers and complete abstracts](https://coralia-io.github.io/coralia-trilogy/) · [Publication metadata and citation exports](publications/README.md).

---

## Author

Emma Cecile · [ORCID](https://orcid.org/0009-0008-4120-9309)

## License

The repository code is MIT licensed. The three Zenodo papers are CC BY 4.0.
