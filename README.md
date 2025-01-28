# PHP Object Reference Gotcha

This repository demonstrates a common yet subtle error in PHP related to object references and how they behave when passed as arguments to functions.  The `bug.php` file shows the problematic code, while `bugSolution.php` offers a corrected approach.  Understanding the difference between pass-by-value and pass-by-reference in PHP is crucial for preventing unexpected behavior in your applications. This example highlights how modifications within a function might not affect the original object if references aren't handled correctly.