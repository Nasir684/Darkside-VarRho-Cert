# DarkSide-20k Var-Rho Certification Study

DarkSide-20k screens roughly a quarter-million SiPM components into 648
photo-detector units, and it has published how it decides: per-tile SNR
above 8, pulse-count-rate tails cut at 1.8 Hz/mm2, breakdown voltage
within 1 V, a production yield of 87%, and correlated-noise anchors of its
own (k_dup = 0.445 ± 0.006; cryogenic correlated delayed avalanches below
0.06 per pulse).

This record asks the natural next question: does a locked, certifiable
screening regime agree with that one? Not a superiority claim — a
side-by-side on identical simulated populations, under criteria frozen
before the first full-study tile exists, every reported rate carrying a
Wilson 95% interval.

The exploratory skeleton (seed 684, archived here) taught three lessons
that now stand as rules:

- **Shared-observable agreement.** A pulse-stream regime cannot see
  breakdown voltage, so D6 judges agreement only where both regimes can
  see — and quantifies the blind region separately, in the open.
- **Anchor to publication.** The correlated band is pinned to the
  collaboration's own published measurements (CDA, k_dup), never to
  population quantiles — the direct cure for the skeleton's 27.9%
  identification figure.
- **The yield-reproduction gate.** No population is admissible until the
  published criteria reproduce the published 87% yield. A simulator that
  cannot reproduce the reference numbers has no business comparing
  screening regimes.

**Contents:** concept note v1.0 (question), exploratory skeleton v0.1
(seed 684, notebook + results + figure), pre-registration v1.0 (falsifiers
D1-D6 fixed, the three rules encoded). The full study runs after the
lock-time fields are filled; Phase 2 (real screening streams) is
conditional on engagement with the collaboration's QA effort.

**Lineage:** QCID-Sigma v5.4 (10.5281/zenodo.23378709) -> muon
pre-registration (10.5281/zenodo.23405991) -> swarm veto protocol
(10.5281/zenodo.23431140) -> swarm validation (10.5281/zenodo.23433610) ->
front-consistency veto (10.5281/zenodo.23482628) -> IceCube DOM study
(10.5281/zenodo.23494707) -> xenon TPC note (10.5281/zenodo.23499555) ->
this record.

**License:** MIT / CC BY. Civilian application.
