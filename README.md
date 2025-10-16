# Simple Calculator

## Overview
Simple Calculator is a clean, responsive, and accessible web-based calculator that supports basic arithmetic operations:
- Addition, subtraction, multiplication, and division
- Decimal numbers
- Percentage
- Sign toggle (±)
- Backspace and All Clear (AC)
- Keyboard input

It is implemented as a single, portable HTML file with inline CSS/JS and works entirely offline.

## Setup
- No build tools or dependencies are required.
- Download the repository contents (or copy the index.html file).
- Open index.html in any modern web browser.

That’s it.

## Usage
- Click or tap the on-screen keys to enter numbers and operations.
- Press = to calculate the result.
- Supported operations:
  - +, −, ×, ÷
  - Percent (%) converts the current entry to a percentage. For addition/subtraction, it uses “percentage of the previous number” behavior.
  - ± toggles the sign of the current entry.
  - AC clears everything; ⌫ deletes the last digit.
- Keyboard shortcuts:
  - Digits: 0–9
  - Decimal point: . (or ,)
  - Operators: +, -, × (use *), ÷ (use /)
  - Equals: Enter or =
  - Backspace: ⌫
  - Clear: Esc or Delete
  - Percent: %

Notes:
- Division by zero yields “Error”. Start typing or press AC to continue.
- Repeated equals (=) repeats the last operation with the last operand (e.g., 5 + 2 = = yields 7 then 9).

## License
MIT License

Copyright (c) 2025 Simple Calculator Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.