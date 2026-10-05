# INDoS WG3 Training School 2026 — structural and diffusion MRI

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23164764.svg)](https://doi.org/10.5281/zenodo.23164764)

Materials for **Block 3** (structural MRI: FreeSurfer, voxel-based morphometry)
and **Block 4** (diffusion MRI), Thursday 1 October.

Part of the **[INDoS WG3 Training School](https://www.indos-costaction.eu/training)**,
Madrid, 30 September to 2 October 2026, run by Working Group 3 (Automated
Preprocessing Pipelines) of COST Action CA24161, INDoS.

## What this is

Teaching materials: notebooks, slides and the notes that go with them. Where
they run on [Neurodesk](https://www.neurodesk.org/), the browser-based
environment the school uses, you will not need to install anything. Where they
do not, the file says what it needs.

They are **free to reuse, adapt and teach from**, including commercially, as long
as you credit the author. One licence covers everything here, notebooks included:
see [LICENSE](LICENSE).

If you use them, please cite the release rather than the repository.
`CITATION.cff` has the details and every release carries a DOI.

Questions, corrections and improvements are welcome as issues or pull requests,
during the school and after it.

## For the maintainer: INDoS conventions

This repository is part of a COST Action deliverable, which puts a few
obligations on it that a personal repository would not have.

### Before the school

- [ ] **Say what your materials need in order to run**, at the top of each file:
      tools, versions, data, and roughly how long it takes.
- [ ] Running on Neurodesk Play Europe, in a browser, from a clean session, is a
      **nice to have and not a requirement**. It is what the school uses and it
      spares everyone an install, but **neither COST nor INDoS mandates it** and
      nothing about this repository depends on it. Do it if it is easy for you;
      do not lose a day to it.
- [ ] Every tool version is pinned and stated. "Latest" is not reproducible, and
      the school is partly about that point.
- [ ] Every dataset used is public and cited by accession and DOI. **No
      participant data, no clinical data, nothing you cannot redistribute.**
- [ ] Anything you did not write yourself is attributed and is compatible with
      CC BY 4.0. If it is not, link to it rather than copy it in.
- [ ] `CITATION.cff` names you correctly, carries your ORCID, and its version and
      date match the release you are about to cut.
- [ ] **Publish a release** once the materials are final, so they carry a DOI
      (see [Publishing a release](#publishing-a-release)).

### In anything you publish from here

> This publication is based upon work from COST Action CA24161 (INDoS),
> supported by COST (European Cooperation in Science and Technology).

### Publishing a release

The citable record on Zenodo comes from GitHub releases, and only from them.
Publishing a release makes **Zenodo** archive it and mint a DOI. `.zenodo.json`
describes the record: a *Lesson*, CC BY 4.0, with the COST acknowledgement.
Pushing to `main` does not touch Zenodo.

Zenodo is connected to this repository by the INDoS organisers. It archives
only releases published after it was switched on, so check with them before
your first release if this repository has no Zenodo webhook under
**Settings, Webhooks**.

To release: **Releases, Draft a new release**, a new tag `v1.0.0` targeting
`main`, a couple of lines on what is in it, **Publish**. Zenodo mints the DOI
within a few minutes. Later changes go out the same way, as `v1.1.0` and so on.

After the first release, put the DOI badge at the top of this README and add the
DOI to `CITATION.cff` (`doi:` and `identifiers:`). Use the **concept DOI**, the
one Zenodo labels "Cite all versions": it always resolves to the latest
release, while the DOI of each release stays pinned to that version.

`.zenodo.json` and `CITATION.cff` describe the same work twice: Zenodo reads only
the first, GitHub's "Cite this repository" only the second. Keep them in step.
