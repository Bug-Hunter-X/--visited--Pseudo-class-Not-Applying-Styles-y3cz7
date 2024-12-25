# :visited Pseudo-class Issue in CSS

This repository demonstrates a problem with the CSS `:visited` pseudo-class.  The issue is that styles defined for visited links are not being applied correctly. The `bug.css` file contains the erroneous CSS, and `bugSolution.css` shows a potential workaround.

## Problem

The `:visited` pseudo-class is intended to style links that the user has already visited. However, in this example, the styles for visited links are not being applied, even after navigating to the linked pages.

## Solution

The issue likely stems from browser security restrictions on styling visited links.  The solution provided in `bugSolution.css` demonstrates a possible workaround by styling based on a class applied to the link after it is visited (using Javascript).
