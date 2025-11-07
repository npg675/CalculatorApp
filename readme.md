# Calculator

A lightweight, front-end calculator suite built with HTML, vanilla CSS, and JavaScript. The project currently includes two calculators:

- **Addition Calculator (`index.html`)** – add three numbers with instant validation and optional dark mode.
- **Simple Interest Calculator (`si.html`)** – compute interest and total amount using the classic `P × R × T ÷ 100` formula, with formatted output and dark mode support.

## Features

- Responsive layouts with smooth animations and gradients.
- Input validation with inline error messaging.
- One-click dark mode toggle persisted via `localStorage`.
- Keyboard support: press `Enter` in any field to run the calculation.

## Project Structure

- `index.html` – main three-number addition calculator.
- `si.html` – simple interest calculator.
- `hello/` – placeholder directory for future assets or pages.
- `info.txt` – project notes (currently unused).

## Getting Started

1. Clone or download the repository to your local machine.
2. Open either `index.html` or `si.html` in your preferred web browser.
3. Enter your values and click the action button (or press `Enter`).

No build tools or package managers are required—the project runs entirely in the browser.

## Usage Tips

- Toggle dark mode using the moon/sun button in the top-right corner.
- Ensure all inputs contain valid numbers; invalid fields highlight errors and pause the calculation.
- Results for the simple interest calculator are formatted to two decimal places for readability.

## Future Ideas

- Expand operations (subtraction, multiplication, division) for the addition calculator.
- Add compound interest and loan amortization calculators.
- Introduce localization (number formats, languages) and accessibility enhancements.
