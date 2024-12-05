# Tailwind CSS @apply Directive: Silent Failure on Misspelled Utility Classes

This repository demonstrates a subtle bug in Tailwind CSS when using the `@apply` directive with a misspelled utility class. The issue is that Tailwind doesn't throw an error when the class is misspelled; it simply doesn't apply the style, leading to unexpected behavior that's hard to debug.

## Reproducing the Bug

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the div with the misspelled class doesn't have the expected red background.