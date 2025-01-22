# Unclosed Inline Element Bug in HTML

This repository demonstrates a subtle yet impactful bug in HTML: a missing closing tag for an inline element (
&lt;span&gt;) nested inside a block-level element (&lt;p&gt;).  This can lead to unpredictable layout issues, particularly in older browsers or when using CSS that relies on strict element nesting.

The `bug.html` file showcases the problem.  The `solution.html` file provides a corrected version with the missing closing tag added.

This type of error can be difficult to debug because the effects aren't always immediately obvious. Careful attention to detail in HTML structure is essential for ensuring consistent and predictable rendering across different browsers and devices.