# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity. The issue arises from unexpected inheritance of styles due to the order and specificity of selectors. The `p` element within the `.container` class should be red, but it's blue due to specificity conflict.  The solution demonstrates how to correctly style the `p` element within the container using more specific selectors.

**Bug:** The styles in `bug.css` show an unexpected color due to a lack of specificity in selector.