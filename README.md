# CSS Hover State Conflict with Visited State

This repository demonstrates a common CSS bug related to conflicts between the `:hover` and `:visited` pseudo-classes.  The issue arises from incorrect style priority and application order. The `bug.css` file shows the problematic code, while `bugSolution.css` provides a corrected version.

## Bug Description

The `:visited` pseudo-class, intended to style visited links, can interfere with the `:hover` pseudo-class, which styles links on mouse hover.  This can lead to unexpected visual results, where the hover effect is not fully applied or is overridden by the visited link style.

## Solution

The solution involves carefully ordering and specifying CSS rules to ensure correct precedence.  The `bugSolution.css` file demonstrates how to resolve the conflict by adjusting the specificity and order of the styles.