# Multi-File Data Matcher

A web-based tool for comparing and matching data across up to 4 CSV or Excel files. Designed for easy, accessible, and flexible data reconciliation.

## Features

- **Upload up to 4 files** (CSV or Excel format).
- **Select up to 4 columns per file** for matching.
- **Name normalization** option for flexible matching (e.g., "Joe Bloggs" matches "Bloggs Joe").
- **Matching modes:**
  - **Match Rows (All Files):** Find rows with matching data in selected columns across all files.
  - **Find Rows with At Least One Match:** Find rows from the first file that match any other file.
  - **Show Non-Matching Rows (From File 1):** Find rows in the first file with no matches in others.
  - **Show Possible Matches (Fuzzy):** Find similar (fuzzy) matches across files using Levenshtein distance.
- **Dual output view:** See results from the top and bottom of the list.
- **Download results** as CSV, with selectable columns.
- **Light/Dark theme toggle** for comfortable viewing.
- **Accessible UI** with keyboard navigation and ARIA labels.

## Usage

1. **Open `FuzzyFileMatcher.html` in your browser.**
2. **Upload files:** Use the file inputs to select up to 4 CSV or Excel files.
3. **Select columns:** Choose columns to match on for each file.
4. *(Optional)* **Enable name normalization** for flexible matching.
5. **Choose a matching mode** by clicking one of the action buttons.
6. **View results** in the output section. Use the bottom view to quickly access the last entries.
7. **Download output:** Select columns and click "Download Output" to save results as CSV.

## Accessibility

- All column selection controls use proper labels and ARIA attributes.
- Keyboard navigation is supported for all controls.

## Requirements

- Modern web browser (no installation needed).
- Files must be in CSV or Excel format.

## Notes

- Fuzzy matching uses a similarity threshold (default 80%).
- Downloaded CSVs reflect the current output and selected columns.
- No data is sent to a server; all processing is done in your browser.

---

*Developed for internal use at London Borough of Croydon. For support, contact your IT department.*
