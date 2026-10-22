# Energy Balance & CO₂ Workflow Demo

An interactive, browser-based prototype by **Yixin Yuan**, independently developed with AI assistance to demonstrate an energy-balance and carbon-accounting workflow.

## What you can explore

- Choose local files and match them by years found in their filenames.
- View a demonstration of the workflow stages.
- Download embedded **Eswatini 2011** example tables and a result ZIP.

## Scope

This is a **workflow demonstration**, not a general-purpose emissions calculator. Its downloadable outputs are fixed examples embedded in the HTML. The interface does **not** parse uploaded workbooks and recalculate their emissions inventories. Progress animation illustrates the process; it is not evidence of a calculation running on the selected files.

## Run locally

Download `index.html` and open it in a modern browser. No package installation or server is required.

The current demonstration interface is in Chinese. This README explains the project in English.

## Implementation and contribution

- Native HTML, CSS and JavaScript.
- Single-file demo with embedded sample downloads.
- Yixin designed the workflow presentation and used AI assistance to develop and refine the implementation.

## Sample data and reuse

The sample tables are supplied with this demonstration. Their presence here does not grant a separate open-data license. Data-source attribution and permission to redistribute the samples should be confirmed before making the repository public. No blanket software or data license is assigned in this preparation package.

## Possible next steps

- Replace the fixed demonstration outputs with a tested workbook-processing pipeline.
- Document input schemas, accounting boundaries, emission-factor sources and units.
- Add validation checks and reproducible example calculations.

These are planned improvements, not currently implemented features.
