# Adolf Kneser, *Lehrbuch der Variationsrechnung* — German text, English and Chinese translations

Adolf Kneser's textbook of the calculus of variations (Braunschweig: Vieweg, 1900): the German text, an English
translation and a Simplified Chinese translation.

| | PDF | LaTeX |
| --- | --- | --- |
| German | [PDF](pdf/Kneser_Lehrbuch_der_Variationsrechnung_German.pdf) (241 pages) | [LaTeX](tex/Kneser_Lehrbuch_der_Variationsrechnung_German.tex) |
| English | [PDF](pdf/Kneser_Lehrbuch_der_Variationsrechnung_English.pdf) (234 pages) | [LaTeX](tex/Kneser_Lehrbuch_der_Variationsrechnung_English.tex) |
| Simplified Chinese | [PDF](pdf/Kneser_Lehrbuch_der_Variationsrechnung_Chinese.pdf) (209 pages) | [LaTeX](tex/zh-hans/Kneser_Lehrbuch_der_Variationsrechnung_Chinese.tex) |

## Completeness

All three readers contain the whole book: the title page, the preface, the table of contents, the list of worked
problems, all 69 sections in eight parts, the bibliography, Kneser's list of errata and the addendum to it.

- The German is a diplomatic transcription. Spelling, notation and misprints are kept as printed. Kneser's list of
  errata is transcribed as printed; its corrections are not carried into the text.
- The 24 figures are reproduced from the scan. Figure 20 is low-resolution in the scan (416 × 214 pixels).
- The readers do not mark the page breaks of the 1900 print. The page numbers in the table of contents and in
  Kneser's cross-references refer to the print.

## How it was made

The German text was transcribed from a scan of the 1900 print, and translated into English and Chinese, by AI
(OpenAI models working in Codex). The Chinese was translated from the German, with the English as an aid. Neither
translation has been reviewed by a person.

## Checks

- During production the transcription was checked against the scan by AI. When the Chinese translation was made,
  the German from the preface to printed page 226 was compared with the print again; this found and corrected two
  formula errors.
- On 27 October 2026 Claude Opus 5.5 (Anthropic) compared the formulas of §30 and printed pages 151, 166, 246, 269
  and 278–280 with the scan. It found that the function Λ of §30 had been read as 𝒜 throughout the section
  (17 places) and that three integrals over the boundary curve 𝔏 on page 279 had ℭ instead. Both are corrected in
  all three languages.
- Printed pages 227–313 have not had a second complete comparison with the print. Expect occasional misread
  symbols there, most likely among the Fraktur letters.

## Source

The transcription follows the Google digitization of the University of Michigan copy, on the Internet Archive as
[lehrbuchdervari00knesgoog](https://archive.org/details/lehrbuchdervari00knesgoog).

## Building

Run `xelatex` twice on each source: the German and English in `tex/` (with the Noto Serif font installed), the
Chinese in `tex/zh-hans/`, which contains the Fandol fonts it uses.

## Rights

Kneser's text is in the public domain. The transcription, translations and typesetting are dedicated to the public
domain under [CC0 1.0](LICENSE). The Fandol fonts in `tex/zh-hans/fonts/` are under the GPL with a font exception;
see the `README` and `COPYING` files there.

## Earlier versions

Earlier versions were published on Zenodo, [doi:10.5281/zenodo.20836971](https://doi.org/10.5281/zenodo.20836971).
Zenodo has blocked access to our account, so please use this repository from now on.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)
