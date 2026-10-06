<!-- En-tête vitrine : remplacer ce commentaire par le bloc de
     https://github.com/zUrp-Astronomics/.github/blob/main/readme-kit/repos/kaiju.md
     (affiche + badge de statut, servis par le site). Collé une fois, il se met à jour seul. -->

# Kaiju — Alt-az Mount

### The final boss of DIY astro: a free, open-source SeeStar on steroids.

**⚠ Work in Progress — NOT VALIDATED — don't build it ⚠**

Smart telescopes are cute: sealed plastic, a tiny sensor behind a tiny lens, and an app that tells you what you're allowed to do. Kaiju takes the same all-in-one idea and removes every limit.

A harmonic alt-az head with an Intel N100 inside — a real computer, not a toy chip — carrying a Samyang AF 135 mm f/1.8 and an APS-C camera. It's built to crush the plastic boxes, not to compete with them.

Kaiju is where the whole zUrp bestiary ends up: Maelstrom behind the glass, Basilisk driving the lens, Kraken feeding the power, Unicorn moving the axes. About 5,000 hours of astro tinkering, condensed into one machine.

Glorious and shiny, but made the low-tech way: it smells of cold coffee, solder flux and a 3D printer that hasn't cooled down in weeks. One cave we refuse to enter is grinding glass. For everything else, buying is cheating.

## Electronics

Kaiju is a purely mechanical project: this repository holds no board, firmware or software. Its electronics is [Unicorn](https://github.com/zUrp-Astronomics/Unicorn), the zUrp mount controller, which lives in its own repository.

## Repository layout

| folder | content |
|---|---|
| `0_Datasheets/` | datasheets of the mechanical components and purchased modules (the electronics' datasheets live in Unicorn) |
| `2_Hardware/` | mechanics: parts (STEP), hardware, mechanical bill of materials |
| `3_3D-Models/` | ready-to-print files (3MF, STL) |
| `7_Docs/` | documentation: design notes |
| `8_References/` | external reference documents |
| `9_Assets/` | README and documentation images; showcase sheet `zurp.yml` and poster, read by the zUrp site |

## License

Licensing: this repository is under OCL v1.1 ([`LICENSE`](LICENSE)). The datasheets in `0_Datasheets/` and the documents in `8_References/` belong to their authors.
