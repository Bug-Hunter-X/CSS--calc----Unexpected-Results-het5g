# CSS `calc()` Unexpected Results

This repository demonstrates a common error when using the CSS `calc()` function: inconsistent units and unexpected order of operations. The `bug.css` file shows the erroneous code, resulting in unexpected layout behavior.  The solution, provided in `bugSolution.css`, addresses these issues by ensuring consistent units and explicit width definitions.

## Bug
The main issue lies in the calculation of the width, where inconsistent units and lack of explicit parent width can cause unexpected results. 

## Solution
The solution employs consistent units (pixels in this case) and ensures that the parent element has its width explicitly defined to allow for accurate `calc()` results.