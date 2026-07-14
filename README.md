# Carboplatin AUC Calculator

Prototype web calculator for renal function estimation and carboplatin AUC-based dose calculation.

## Features

- Adult eGFR equations
  - 2021 CKD-EPI Creatinine
  - 2021 CKD-EPI Creatinine-Cystatin C
  - 2012 CKD-EPI Cystatin C
- Pediatric, adolescent, and young adult equations
  - CKiD U25 Creatinine
  - CKiD U25 Cystatin C
  - CKiD U25 Creatinine-Cystatin C
  - 2009 CKiD Bedside equation
- 24-hour urine creatinine clearance
- Mosteller BSA calculation
- Raw GFR, Normalized GFR, and GFR normalized to patient BSA conversions
- Carboplatin formulas
  - Calvert
  - Newell
  - Mann/Pein
  - Marina/St. Jude
- Estimated GFR cap comparison for Calvert calculations
- Copyable summary and print-friendly output

## Important warning

This project is a prototype for testing and independent verification only. It has not completed formal clinical validation and must not be used as the sole basis for prescribing. All calculations must be independently verified by qualified healthcare professionals before clinical use.

Do not enter patient names, medical record numbers, dates of birth, or other identifiable information.

## Privacy

All calculations are performed locally in the browser. This static version does not intentionally upload or store entered clinical data on a server.

## Running locally

Download `index.html` and open it in a modern browser such as Chrome, Edge, Firefox, or Safari.

## GitHub Pages deployment

1. Upload all files in this repository to the `main` branch.
2. Open repository **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`.
6. Save the setting.

The site address will normally be:

`https://<username>.github.io/carboplatin-auc-calculator/`

## Version

Prototype v0.1 — July 2026
