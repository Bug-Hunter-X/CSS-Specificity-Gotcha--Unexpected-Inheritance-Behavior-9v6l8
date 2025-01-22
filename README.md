# CSS Specificity Issue: Unexpected Inheritance

This repository demonstrates a common CSS specificity problem.  A paragraph (`<p>`) element nested within a `div` unexpectedly inherits the parent's color, despite a more specific selector being defined.

## Problem
The `bug.css` file contains the problematic CSS code.  Observe the unexpected color of the paragraph within the div when rendered in a browser.

## Solution
The `bugSolution.css` file presents the corrected CSS. This solution addresses the specificity issue by ensuring the intended styles override inherited values.  Review the changes made to resolve the conflict and achieve the desired outcome.

This example highlights the importance of understanding CSS selector specificity to avoid unintentional styling behaviors.