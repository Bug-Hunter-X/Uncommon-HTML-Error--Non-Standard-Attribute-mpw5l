# Uncommon HTML Error: Non-Standard Attribute

This repository demonstrates an uncommon HTML error involving the use of non-standard attributes.  While browsers generally ignore these attributes, they can potentially lead to unexpected behavior, particularly when interacting with JavaScript frameworks or libraries.

## The Bug
The `bug.html` file contains an example of this error.  A non-standard attribute, `data-invalid-attribute`, is used on a `div` element.  While this will likely render without immediate visible issues, it's considered bad practice and can potentially lead to unexpected behaviour or conflicts.

## The Solution
The `bugSolution.html` file demonstrates the corrected code, removing the non-standard attribute to maintain cleaner, more standards-compliant HTML.

## Reproducing the Bug
1. Clone this repository.
2. Open `bug.html` in your web browser.  Observe that the content renders, although the non-standard attribute might be silently ignored by the browser.
3.  (Optional) Try using a browser developer console or debugging tools to potentially see any warnings or issues related to the non-standard attribute.

## Fixing the Bug
Use only standard and well-defined HTML attributes.  If you need to add custom data, use a valid method like `data-*` attributes, but make sure these are handled appropriately by your application or framework.