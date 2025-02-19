# Tailwind CSS Subtle Bugs

This repository demonstrates a couple of subtle bugs that can occur when using Tailwind CSS.  The first involves gradients that are too similar in color, resulting in a barely noticeable gradient. The second showcases a common error of improperly applying utility classes, causing unintended styling effects.

## Bug 1: Imperceptible Gradients
The gradient in `bug.js` uses colors that are too close, making the effect barely visible. This highlights the importance of choosing distinct colors for effective gradient application.

## Bug 2: Utility Class Misplacement
The second bug (not explicitly shown in code, but described in bug.js comments) demonstrates how incorrect placement of utility classes can lead to styling problems.  Proper understanding of Tailwind's class precedence is crucial to avoid this.

## Solutions
The `bugSolution.js` file provides corrected code demonstrating better color choices for the gradient and proper class placement to address these issues.