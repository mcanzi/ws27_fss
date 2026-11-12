# Introduction to Forensic Speech Science

Slides for *Introduction to Forensic Speech Science* (Dr Massimiliano Canzi, Department of Linguistics, University of Konstanz), summer semester 2027. The sessions follow the chapters of Leemann, A., Perkins, R., Sullivan Buker, G., & Foulkes, P. (2024), *An Introduction to Forensic Phonetics and Forensic Linguistics*, Routledge: chapters 1 to 7 (forensic phonetics and LAAP), chapters 10 to 12 (language in the legal process and authorship analysis) and chapter 13 (expert witnesses). Sessions 8 and 9 are built from the original studies those chapters cover. The figures use simulated data, except for published results that are labelled as such (for example McGehee, 1937, in session 5).

| | Session | Chapter |
|---|---|---|
| 1 | Course introduction | 1 |
| 2 | Phonetic analysis | 2 |
| 3 | Speaker profiling | 3 |
| 4 | Speaker comparison | 4 |
| 5 | Earwitness evidence | 5 |
| 6 | Authentication, enhancement and speech content | 6 |
| 7 | Linguistic analysis in the asylum procedure | 7 |
| 8 | Language in the legal process | 10 |
| 9 | Authorship analysis | 11, 12 |
| 10 | Expert witnesses | 13 |
| 11 | Praat practical 1: measuring your own voice | 2, 4 |
| 12 | Praat practical 2: casework with the class recordings | 3–5 |

The slides are online at [mcanzi.github.io/ws27_fss](https://mcanzi.github.io/ws27_fss/01_course_introduction.html).

## Rendering the slides

Knit `source/render_all.Rmd` to render every session into `docs`, which GitHub Pages serves. Knitting a single session also writes its HTML into `docs`. All sessions use the sunset theme of mcanzi.github.io (`source/theme-sunset.css`): the colours of a sunset over Almaty, with oranges drawn in ink in the background; `source/slides_setup.R` sets the plot colours to match it (orange, dusk blue and pink for groups). The fonts are in `source/fonts` and are embedded in each HTML file.

Requires `tidyverse` and `revealjs`; optional: `qrcode` (QR codes), `ragg` and `systemfonts` (Atkinson Hyperlegible in the figures).

## License

Course materials © Massimiliano Canzi, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE.md`). Code is licensed under the MIT License (see `LICENSE-CODE.md`). The fonts used in the slide theme (Atkinson Hyperlegible, Bricolage Grotesque, JetBrains Mono) are licensed under the SIL Open Font License 1.1 (see `source/fonts/OFL-*.txt`).
