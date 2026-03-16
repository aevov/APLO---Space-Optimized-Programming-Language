# Contributing to APLO

Thank you for your interest in contributing to the APLO ISA Specification.

---

## What You Can Contribute To

The APLO repository contains two distinct components with different governance:

| Component | License | Contributions Accepted? |
|---|---|---|
| APLO ISA Specification | Apache 2.0 (see `LICENSE_ISA.md`) | ✅ Yes |
| `aplo_compiler.js` | Proprietary | ❌ No (maintained by Aevov) |
| `aplo_demo.html` | Proprietary | ❌ No |
| aevov.space platform | Proprietary | ❌ No |

**Open for contribution:**
- APLO ISA Specification documents
- Example programs written in APLO
- Test suites and conformance tests for the ISA
- Documentation, tutorials, and educational materials
- Bug reports against the ISA specification (ambiguities, gaps)
- Domain-specific ISA extension proposals (clearly marked as non-canonical)

---

## Contribution Process

### 1. Specification Issues

If you find an ambiguity, error, or gap in the APLO ISA Specification:

1. Open a GitHub Issue with the label `spec-bug` or `spec-clarification`
2. Reference the specific section and clause
3. Provide a concrete example that demonstrates the ambiguity
4. Suggest a resolution if possible

### 2. Example Programs

APLO programs contributed to `/examples/` must:

1. Be original work authored by the contributor
2. Include a comment block specifying:
   - Algorithm name and description
   - Bit count breakdown (base glyphs + compounds)
   - Expected output / quantum state
3. Be verifiable against `aplo_compiler.js`

### 3. ISA Extension Proposals

If you want to propose an extension to the APLO ISA (e.g., for terrestrial
applications, new quantum operations):

1. Open a GitHub Discussion under the `ISA-RFC` category
2. Use the RFC template (see `/docs/RFC_TEMPLATE.md`)
3. Extensions must be clearly namespaced: `APLO-EXT-<name>` (not `APLO`)
4. Extensions do not become part of the canonical APLO ISA without explicit
   written approval from Aevov Corporation

### 4. Conformance Tests

Conformance tests help third-party implementors verify their ISA implementations:

1. Tests must be deterministic and hardware-independent
2. Each test must specify: input glyph sequence, expected bytecode, expected
   simulation result
3. Submit as a PR to `/tests/conformance/`

---

## Contributor License Agreement (CLA)

Before your contribution can be accepted, you must agree to the APLO CLA.

**By submitting a pull request, you agree that:**

1. You are the original author of the contribution, or have the right to submit it
2. You grant Aevov Corporation a perpetual, irrevocable, worldwide, royalty-free
   license to use, reproduce, modify, and distribute your contribution as part of
   the APLO ISA Specification under Apache 2.0
3. You retain copyright in your contribution
4. Your contribution does not include any third-party proprietary material

For contributions from employees of companies, the CLA must be signed by an
authorized representative. Contact orion@aevov.space for the corporate CLA form.

---

## Code of Conduct

APLO is built for humanity's expansion into space. Contributions are expected to
reflect that ambition:

- Be precise. Ambiguity in an ISA specification has real consequences.
- Be collegial. Disagreements on design are expected; disrespect is not.
- Be honest about uncertainty. If you don't know, say so.
- Cite your sources. Mathematical claims should reference established literature.

---

## Recognition

Significant contributors to the APLO ISA Specification will be recognized in:
- The specification document's acknowledgements section
- The CONTRIBUTORS file in this repository
- Aevov's annual technical report

---

## Questions

For contribution questions: open a GitHub Discussion  
For licensing questions: orion@aevov.space  
For partnership and research collaboration: orion@aevov.space

*aevov.space*
