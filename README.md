# CSS :hover Pseudo-class Interference

This repository demonstrates a common yet subtle issue in CSS where the `:hover` pseudo-class on a parent element is overridden by a child element's hover effect.

The bug.css file contains the problematic code, while the solution.css file presents a solution.

## Bug Description

The intended behavior is for the `.parent` element's background color to change when hovering over it. However, only the `a` element's styling changes.

## Solution

This issue is resolved by using a more specific selector for the parent's hover effect, preventing the child element's hover from overriding it.