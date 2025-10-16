# Simple Calculator (Round 2)

MIT Licensed, zero-dependency web calculator supporting addition, subtraction, multiplication, and division with graceful divide-by-zero handling.

## Overview
This is a lightweight, single-file web app that lets you:
- Compute +, -, ×, ÷ between two numbers
- See results instantly by clicking an operator or pressing Enter
- Get friendly errors instead of Infinity when dividing by zero

Accessibility highlights:
- Clear labels and focus styles
- aria-live regions for result updates and errors
- Keyboard shortcuts (Enter to calculate, Esc to clear, and + - * / to switch operation)

License: MIT (see below).

## Setup
- No build steps or dependencies required.
- Open index.html in any modern web browser.

Optional:
- Serve via a local server (e.g., npx serve .) for best file URL behavior.

## Usage
1. Enter values in “Number A” and “Number B”.
2. Choose an operation:
   - Click an operator button (+, −, ×, ÷) to calculate immediately, or
   - Press +, -, *, or / on your keyboard to select the operation.
3. Press Enter or click “Calculate” to compute again using the last selected operation.
4. Press Esc or click “Clear” to reset inputs.

Divide-by-zero behavior:
- If you attempt A ÷ 0, the calculator shows a clear error message and withholds a numeric result.

Notes:
- Inputs accept integers and decimals.
- Results are lightly normalized to reduce floating-point artifacts.

## Improvements in Round 2
From the previous version, this release adds:
- Multiplication (×) support
- Division (÷) support
- Graceful divide-by-zero handling with a clear error message
- Minor UX polish: active operator highlighting, keyboard shortcuts, improved result formatting

## MIT License
Copyright (c) 2025 Simple Calculator Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.