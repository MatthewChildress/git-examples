# git-examples


This is the exampleOneA branch.

Git allows you to create branches from branches.

Be mindful of where in the git tree you're branching from though for merging back into main.

A good use case for this would be two or more people working in the same dev branch to fix a section of code.

you can directly merge this branch into main.

while in main branch
Ex - git merge exampleOneA

It's safter to merge it into its parent branch though since you're further abstracted away from main.

whilein exampleOne

Ex - git merge exampleOneA