diff --git a/README.md b/README.md
new file mode 100644
index 0000000000000000000000000000000000000000..41473b78efd176f6e7f95df4268d856345735a25
--- /dev/null
+++ b/README.md
@@ -0,0 +1,20 @@
+# IES Excel Visualizer
+
+Upload an Excel workbook exported from Microsoft Forms and instantly build charts without changing the code each semester.
+
+## How to use
+1. Open `index.html` in your browser (no server required).
+2. Click **Upload Excel file** and choose your workbook.
+3. Pick the sheet you want to explore.
+4. Select the X and Y fields and choose a chart type (bar, line, or pie).
+5. View the live chart and table preview (first 50 rows) to validate your data.
+
+> Tip: save the workbook with the same column names each semester so you can reuse your chart selections.
+
+## Tech
+- [SheetJS](https://sheetjs.com/) to parse Excel files in the browser.
+- [Chart.js](https://www.chartjs.org/) for quick visualizations.
+- Vanilla HTML/CSS/JS for a lightweight setup.
+
+## Development
+No build steps are required. Edit the HTML, CSS, or JS files directly, refresh the page, and re-upload a workbook to test your changes.
