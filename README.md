# Forensic Speech Science

Slides for *Forensic Speech Science* (Dr Massimiliano Canzi, Department of Linguistics, University of Konstanz). Each session follows one chapter of Leemann, A., Perkins, R., Sullivan Buker, G., & Foulkes, P. (2024), *An Introduction to Forensic Phonetics and Forensic Linguistics*, Routledge: chapters 1 to 7 (forensic phonetics and LAAP) and chapter 13 (expert witnesses). The figures use simulated data, except for published results that are labelled as such (for example McGehee, 1937, in session 5).

| | Session | Chapter |
|---|---|---|
| 1 | Course introduction | 1 |
| 2 | Phonetic analysis | 2 |
| 3 | Speaker profiling | 3 |
| 4 | Speaker comparison | 4 |
| 5 | Earwitness evidence | 5 |
| 6 | Authentication, enhancement and speech content | 6 |
| 7 | Linguistic analysis in the asylum procedure | 7 |
| 8 | Expert witnesses | 13 |

## Rendering the slides

Knit `source/render_all.Rmd` to render every session into `docs`, which GitHub Pages serves. Knitting a single session also writes its HTML into `docs`. All sessions use the purple theme of mcanzi.github.io (`source/theme-purple.css`); `source/slides_setup.R` sets the plot colours to match it. The fonts are in `source/fonts` and are embedded in each HTML file.

Requires `tidyverse` and `revealjs`; optional: `qrcode` (QR codes), `ragg` and `systemfonts` (Atkinson Hyperlegible in the figures).

## License

Course materials © Massimiliano Canzi, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE`). Code is licensed under the MIT License (see `LICENSE-CODE`). The fonts used in the slide theme (Atkinson Hyperlegible, Bricolage Grotesque, JetBrains Mono) are licensed under the SIL Open Font License 1.1.
