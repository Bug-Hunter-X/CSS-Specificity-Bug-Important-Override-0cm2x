# CSS Specificity Bug: !important overridden

This repository demonstrates an uncommon bug in CSS related to selector specificity.  The `!important` declaration, while powerful, can be overridden by a more specific selector. This example highlights this behavior, showing how a more specific selector takes precedence over a selector with `!important`.

## Bug Description:
The provided CSS demonstrates that a more specific selector (id + class) takes precedence over a less specific selector (class) even when the less specific one has the `!important` declaration. This is counter-intuitive to developers unfamiliar with the nuances of CSS specificity.

## Solution:
The solution involves understanding CSS selector specificity.  To ensure the desired color application, either avoid using `!important` or make sure the selector with `!important` is more specific. 

This is a valuable learning experience to showcase the complexity of CSS specificity and when to leverage `!important` carefully.