# Tailwind CSS Specificity Bug

This repository demonstrates a common but often overlooked issue in Tailwind CSS: unexpected CSS specificity problems.  This can lead to styles not applying as expected due to unintentional specificity conflicts.

The `bug.js` file contains example code showcasing the problem where a higher-specificity styles unexpectedly overrides a lower-specificity style, even if the intended behavior is to have the lower-specificity style take precedence.

The `bugSolution.js` file provides potential solutions to address this problem, such as using important or more specific classes. The best method will depend on the specifics of your project and CSS architecture.  This bug is not specific to Tailwind, but Tailwind's utility-first approach can make it more prevalent.