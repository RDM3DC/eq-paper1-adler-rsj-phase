# Phase (Adler/RSJ) Dynamics


<!-- HERO_ANIMATION:BEGIN -->
![Adler / RSJ phase dynamics](images/adler_phase_dynamics.gif)

_Hero animation: **Adler / RSJ phase dynamics**. [Download high-resolution MP4](images/adler_phase_dynamics.mp4)._
<!-- HERO_ANIMATION:END -->

**ID:** `eq-paper1-adler-rsj-phase`  
**Tier:** derived  
**Score:** 96  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
\dot{\phi}=\Delta-\lambda\,G\,\sin\phi
$$

## Description

Unwrapped phase difference φ(t) tries to run at detuning Δ, but adaptive coupling λG can pull it into a locked fixed point. Backbone equation of the parity-locking mechanism. Textbook Adler/RSJ form with ARP-adaptive coupling.

## Assumptions

- Single junction / single mode approximation.
- λG is the effective adaptive coupling strength (positive, ARP-governed).
- Detuning Δ is constant or slowly varying compared to phase dynamics.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id eq-paper1-adler-rsj-phase --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
