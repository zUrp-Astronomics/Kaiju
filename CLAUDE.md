# Kaiju

Mechanical design of Kaiju, the zUrp Astronomics all-in-one alt-az astro head. This repository holds
mechanics only: no board, firmware or software, so there is nothing to build or test. Its folders
hold only their `README.md` for now.

## Conventions

- `README.md`, `9_Assets/`, `LICENSE`, `LICENSE-HARDWARE` and `.github/workflows/zurp-site.yml` are the
  showcase, written by the zUrp-Astronomics organisation for all its products at once: a project
  ticket does not touch them.
- The `0_` to `9_` folder tree and the naming of board files are defined once, by the organisation, in
  § 5 of the kit: https://github.com/zUrp-Astronomics/.github/blob/main/readme-kit/README.md — follow
  it, do not restate it here.
- Kaiju's electronics live in the Unicorn repository (https://github.com/zUrp-Astronomics/Unicorn),
  not here: no board files in this repository, and `0_Datasheets/` only takes datasheets of mechanical
  components and purchased modules.
- What each folder takes is said in its own `README.md`.

## Doc

Project documentation (manual, protocol, design notes) goes in `7_Docs/`; the root `README.md` stays
the entry point.
