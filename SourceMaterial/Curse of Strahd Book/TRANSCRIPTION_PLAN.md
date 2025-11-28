Title: Transcription Plan — "Curse of Strahd Book"

Source PDF: https://raw.githubusercontent.com/mstmagic/Curse-of-Strahd/main/SourceMaterial/Curse%20of%20Strahd%20Book.pdf

Status: In progress — initial structure created.

Objective:
- Produce a high-quality Markdown transcription of the PDF, broken into chapter files.
- Preserve headings, subheadings, tables, lists, and images (images will be extracted as separate files when available).
- Use clear, sequential filenames to reflect reading order.

Planned workflow:
1. Retrieve a machine-readable copy of the PDF (OCR if required).
2. Identify the table of contents and map its chapters to separate markdown files named with two-digit prefixes (01_, 02_, ...).
3. Transcribe chapter-by-chapter. For long chapters, split into subfiles using decimal numbering (e.g., 03.01_...).
4. Preserve formatting: use H1/H2/H3 equivalents, code blocks for examples, and fenced blocks for notable excerpts.
5. Extract images and handouts into the same directory under an "assets/" subfolder and reference them relative to their chapter.
6. Create an index (README.md) with links to all chapter files and a progress checklist.

Naming convention (applied consistently):
- 01_Chapter_Title.md
- 02_Chapter_Title.md
- assets/ for images and extracted media
- README.md to serve as the chapter index and navigation

Next steps (automated/manual):
- Begin OCR and text extraction for first pages and populate 01_Chapter_01.md.
- Commit intermediate transcriptions in small, reviewable chunks.

Notes:
- This file is a working plan. Actual chapter titles and counts will be updated once the table of contents is parsed.
