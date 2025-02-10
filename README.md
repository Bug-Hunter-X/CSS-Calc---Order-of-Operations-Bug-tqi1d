# CSS Calc() Order of Operations Issue

This repository demonstrates a subtle bug related to the order of operations within CSS's `calc()` function. When combining percentages and fixed units (like pixels), the calculation might not produce the expected result if the order isn't carefully managed.

The `bug.css` file shows the problematic code.  `bugSolution.css` presents the corrected version.

This issue can be particularly frustrating to debug because the error might only manifest under certain conditions or in specific browser contexts.  Understanding how `calc()` processes units is key to avoiding these pitfalls.