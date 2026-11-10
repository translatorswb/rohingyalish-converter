# Rohingyalish converter

Converts old-style Rohingyalish (Latin script: `*`, `sh`, `R`, hyphens, apostrophes, no stress marks) to the current standardized form developed in the LT4CR project.

**Use it:** https://translatorswb.github.io/rohingyalish-converter/

- Paste text, or upload a `.txt` / `.tsv` file. For a TSV, pick the column to convert, plus an optional column with names to protect (e.g. the English sentence).
- Every changed word is highlighted, and you can see which rule changed it.
- Download the result (`.txt`, or the TSV with `converted` and `changes` columns added) and the list of changes.
- The **Knowledge base** tab lists the rules, spelling corrections, marker tables and dictionary accents the converter uses.

Everything runs in your browser and no text is uploaded. You can also download `index.html` and open it offline.

The standard is still evolving, so always review the output.

---
This repository holds only the built page. It is generated from the converter's knowledge base (`rhg-standard/app/build_app.py`) and has to be republished when the knowledge base changes.

Maintained by CLEAR Global / TWB.
