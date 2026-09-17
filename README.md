# INDoS WG3 Training School 2026 — structural and diffusion MRI

Materials for **Block 3** (structural MRI: FreeSurfer, voxel-based morphometry)
and **Block 4** (diffusion MRI), Thursday 1 October.

Part of the **[INDoS WG3 Training School](https://www.indos-costaction.eu/training)**,
Madrid, 30 September to 2 October 2026, run by Working Group 3 (Automated
Preprocessing Pipelines) of COST Action CA24161, INDoS.

## What this is

Teaching materials: notebooks, slides and the notes that go with them. They are
written to run in a browser on [Neurodesk](https://www.neurodesk.org/), which is
the environment the school uses, so you should not need to install anything to
follow them.

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

- [ ] Materials run start to finish on Neurodesk Play Europe, in a browser, from
      a clean session. If anything else is needed, say so at the top of the file.
- [ ] Every tool version is pinned and stated. "Latest" is not reproducible, and
      the school is partly about that point.
- [ ] Every dataset used is public and cited by accession and DOI. **No
      participant data, no clinical data, nothing you cannot redistribute.**
- [ ] Anything you did not write yourself is attributed and is compatible with
      CC BY 4.0. If it is not, link to it rather than copy it in.
- [ ] `CITATION.cff` names you correctly, carries your ORCID, and its version and
      date match the release you are about to cut.
- [ ] **Cut a release and let Zenodo mint a DOI**, by **29 September**, so the
      materials are citable on the day rather than months later.

### In anything you publish from here

> This publication is based upon work from COST Action CA24161 (INDoS),
> supported by COST (European Cooperation in Science and Technology).

### Connecting Zenodo, once

1. Sign in at [zenodo.org](https://zenodo.org) **with GitHub**.
2. If the authorisation screen asks, grant access to the **indos-costaction**
   organisation. This step is easy to miss on an organisation-owned repository,
   and it is the usual reason a repository never shows up in the list.
3. Zenodo, your account, **GitHub** tab: find this repository and switch it
   **ON**.
4. Only releases created **after** the switch is on are captured. Turning it on
   afterwards does nothing for a tag that already exists.
5. On GitHub: **Releases, Draft a new release**, tag `v1.0.0`, target `main`,
   two lines about what is in it, **Publish**.
6. Zenodo archives the tag and mints a DOI within a few minutes.
7. Put the DOI badge at the top of this README, and add the DOI to
   `CITATION.cff` (`doi:` and `identifiers:`).
8. Zenodo types the record as *Software* by default. Open the record and change
   the resource type to **Lesson**, which is what this is.

Tag `v1.1.0` after the school for whatever the three days turn up. The DOI from
step 6 always resolves to the latest version, so the citation does not go stale.
