# Moon's Calculator

Simple Bootstrap-based web app to calculate total cardboard cost.

Formula used:

total = (rate + rental) / 2400 * measure

where measure = width × height × length (cubic measure).

How to use:

1. Open `index.html` in your browser (double-click or use a local server).
2. Fill in Rate (Rs), Rental Cost (Rs), Width (in), Height (in) and Length (in). You can leave any field blank — it will be treated as 0.
3. Click Calculate. The result and measure will appear below the form.

Notes / assumptions:
# Product Rate Calculator

This project now implements the single-file "Product Rate Calculator" app. The UI, styles and calculation logic are all contained in `index.html`.

What it calculates
- Individual components (Plate, Card, Printing, Lamination, Dye Making, Dye Karai, Binding, Nali, Silicat).
- A summary table and a grand total (all amounts shown in PKR, e.g. "123.45 RS").

How to run
1. Open `index.html` in your browser (double-click) or serve the folder with a local server.

Notes
- Inputs accept numeric values. Some component calculations require all fields present (the app will prompt if a required field is missing).
- This replaced the previous Moon's Calculator files; old separate CSS/JS files were removed and the app is now self-contained.

If you want me to split CSS/JS back into separate files, add unit conversion, or change currency formatting, tell me which change and I will implement it.
