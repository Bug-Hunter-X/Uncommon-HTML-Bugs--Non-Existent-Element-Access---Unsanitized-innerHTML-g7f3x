# Uncommon HTML Bugs

This repository demonstrates two uncommon HTML bugs:

1. **Attempting to access a non-existent element:**  Accessing a DOM element that doesn't exist leads to a null reference error.
2. **Using innerHTML with unsanitized user input:** Directly inserting user input into the DOM using innerHTML is a security risk.  It's vulnerable to cross-site scripting (XSS) attacks.

The `bug.html` file shows the buggy code. The `solution.html` file provides corrected versions.  Best practices for preventing these issues are also included in the comments.