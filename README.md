# Date Duration Calculation in Latex
Given a past month and year, calculate and display how many months and years have elapsed.

Usage:
- Add the `date_duration_func.tex` file to your Latex directory and include it in your document by adding `\input{date_duration_func}` before `\begin{document}`.
- Call the `Duration` function with `\Duration{M}{YYYY}`, where M is an integer for the month, and YYYY is an integer for the year.
- Function will display the elapsed months and years since the inputted date, correctly accounting for plurals and other cases.

Some examples are shown in the included example document, `main.tex`.


