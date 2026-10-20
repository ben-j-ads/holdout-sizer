# Holdout Sizer

Can your audience actually tell you whether the ads work? Enter the audience, baseline conversion rate, test length, holdout share and the smallest lift worth knowing, and get a verdict before you spend on a holdout test.

Open `index.html` in any browser. No build step and no dependencies.

- **Verdict:** `testable`, `borderline` or `can't test this`, from the power of a two-proportion test.
- **Also shows:** the smallest lift your setup could see, the audience or weeks needed for your power target, expected conversions in the control group, and the conversions you give up by holding people out.
- **Trade-off table:** power, smallest visible lift and cost for holdouts from 5% to 50%.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

Treats people as independent units with no leakage, which is the best case. A geo test has few units and needs more. Under about 50 expected control conversions the normal approximation is shaky, and the tool says so.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
