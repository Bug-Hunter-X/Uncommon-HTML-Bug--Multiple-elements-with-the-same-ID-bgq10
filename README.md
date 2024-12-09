# Uncommon HTML Bug: Multiple elements with the same ID

This repository demonstrates a subtle bug that can occur in HTML when dealing with IDs and accessing elements.

## The Bug
The `bug.html` file contains HTML code with multiple elements that share the same ID.  This is invalid HTML, and although some browsers might seemingly work with it, it will result in unexpected behavior.  Additionally, there is an example of using `getElementsByTagName` without a proper index; this may appear to work in some cases but is unreliable.

## The Solution
The `bugSolution.html` file shows the correct way to structure the HTML and access elements, avoiding the ambiguity of duplicate IDs. IDs must be unique.  It also shows the proper use of `getElementsByTagName` along with index.