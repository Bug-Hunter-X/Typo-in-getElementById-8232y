# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle yet common error in JavaScript when interacting with HTML elements.

The bug lies in a simple typo in the `getElementById` method, which is frequently used to access elements by their ID.

## Bug Description
The provided HTML code attempts to modify the content of a div element using the incorrect method `getElementByIdx`.

## Bug Solution
The solution replaces `getElementByIdx` with the correct method `getElementById`.

## How to reproduce the bug
1. Open `bug.html` in a web browser.
2. Observe that the content of the div element does not change because `getElementByIdx` is not a valid method.

## How to fix the bug
1. Open `solution.html` in a web browser.
2. Observe that the content of the div element correctly changes to "<p>Text changed!</p>"