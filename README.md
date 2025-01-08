# CSS Specificity and Inheritance Bug

This repository demonstrates a common, yet often overlooked, issue in CSS: unexpected inheritance behavior due to specificity. The bug showcases a scenario where a more specific selector is overridden by a less specific one due to inheritance.

## Bug Description

The bug lies in the incorrect application of CSS styles due to a misunderstanding of CSS specificity and inheritance. A paragraph element nested within a div element inherits styling from both the `div` and `p` selectors. However, due to inheritance rules and specificity, the less specific rule unexpectedly overrides the intended styling.

## Bug Reproduction

1. Clone the repository.
2. Open `bug.css` to review the problematic code.
3. Open the corresponding HTML file (not included in this simplified example but easily created to test) and observe the unexpected styling on paragraphs within the div.

## Solution

The solution involves understanding and correcting the CSS specificity and inheritance issue. Modifying the CSS to ensure the intended selector has higher specificity will resolve the problem.  See the `solution.css` file for a corrected version.

## Lessons Learned

This example highlights the importance of understanding CSS specificity and inheritance when writing stylesheets. Always consider specificity when adding styles to avoid unexpected behaviors.