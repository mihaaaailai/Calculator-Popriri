# Calculator Popriri Salariu & Fracții (Salary Garnishment & Fractions Calculator)

## Description

This is a simple, web-based calculator built as a single HTML file with embedded CSS and JavaScript. It serves two main purposes:

1.  **Simple Fraction Calculation:** Quickly calculates common fractions (1/2, 1/3, 2/3) of a given salary amount.
2.  **Salary Garnishment Calculation:** Estimates the maximum amount that can be legally garnished from a salary in Romania, based on user inputs regarding different types of active garnishments (ANAF, Primărie/Local Taxes, BEJ) and optional minimum wage protection rules.

The user interface is presented in **Romanian**.

## Features

* **Dual Functionality:** Acts as both a simple fraction calculator and a more complex salary garnishment estimator.
* **Garnishment Types:** Allows users to specify active garnishments from:
    * ANAF (National Agency for Fiscal Administration)
    * Primărie / Impozite Locale (City Hall / Local Taxes)
    * BEJ (Birou Executor Judecătoresc - Judicial Enforcement Office)
* **Minimum Wage Protection:** Option to apply the Romanian minimum wage threshold, ensuring a protected amount remains for the employee (calculates based on half the net minimum wage). The minimum wage value is pre-filled but can be adjusted.
* **Multiple BEJ Cases:** Input field for the number of active BEJ cases.
* **Dynamic UI:** Relevant input fields (like minimum wage, number of BEJ cases) appear only when their corresponding options are checked.
* **Clear Results:** Displays the total amount garnished and the remaining salary after deductions. For garnishments, it provides a simplified estimation of how the garnished amount might be distributed among the active creditors.
* **Input Validation:** Basic checks for valid numerical inputs.
* **Reset Functionality:** Easily clear all inputs and results.
* **Responsive Design:** Basic styling ensures usability on different screen sizes.
* **Standalone:** Runs entirely in the browser; no server-side processing or internet connection required after loading (except for Google Fonts).

## Technologies Used

* HTML5
* CSS3 (including CSS Variables and Gradients)
* Vanilla JavaScript (ES6+)
* Google Fonts (Poppins)


## Important Notes & Limitations

* **Simplified Logic:** The JavaScript code for garnishment calculation contains comments indicating that the logic is **simplified** (`Logica de Calcul Popriri (SIMPLIFICATA)`, `Distribuirea sumei retinute (SIMPLIFICATA)`). It aims to respect the general maximum caps (1/3 or 1/2 of salary) and minimum wage protection but might **not** cover all specific legal nuances, priorities between creditors, or special cases (e.g., child support garnishments which often have higher limits).
* **Minimum Wage Value:** The default minimum wage value (`2574 RON` in the code) is an example and **must be verified against current official sources** for accurate calculations when using the minimum wage protection feature.
* **Estimation Only:** This tool provides an estimation based on the implemented rules. It should **not** be considered definitive legal or financial advice. Consult with legal professionals or relevant authorities for precise figures and legal implications.
