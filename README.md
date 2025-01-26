# Unexpected CSS blur behavior with position: fixed

This repository demonstrates a common issue where applying the `filter: blur()` CSS property to an element with `position: fixed` can lead to unexpected rendering results. The blur effect might be clipped, invisible, or affect elements in unintended ways. 

The `bug.css` file contains the problematic CSS, and `solution.css` demonstrates a potential solution.

**Problem:**  The blur is applied incorrectly to a fixed element.

**Solution:**  Potential solutions include using a different positioning method or adjusting the context where blur is applied (e.g., using a wrapper element).