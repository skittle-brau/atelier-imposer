# atelier-imposer
A simple tool for arranging/imposing PDFs for print

## Usage

Open `index.html` in a browser, then open or drop a PDF onto the page. Everything runs locally in the browser; files are never uploaded. The page loads pdf-lib and PDF.js from cdnjs, so it needs an internet connection.

## Features

- **Layouts:** step & repeat, N-up, cut & stack, and saddle-stitch booklet
- **Double-sided:** pages 1/2, 3/4 and so on become front/back pairs, with work & turn or work & tumble backs
- **Sizing:** trim from the PDF TrimBox, the whole page, a bleed inset or a custom size; sheet presets (Letter, Tabloid, 12×18, 13×19, A4/A3, SRA3/SRA4, B2) or a custom sheet; automatic best fit or a manual grid
- **Bleed and gutters:** adjustable bleed per item, gutters between columns and rows, minimum sheet margin
- **Marks:** crop marks, registration targets and a slug line
- **Guillotine cut chart:** every cut position measured from the sheet edges
- **Saved setups:** stored in the browser
