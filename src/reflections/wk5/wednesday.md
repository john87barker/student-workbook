# Wednesday

## In simple terms what is a sub-document?
A schema inside another schema
## When might you use a sub-document?
When you need to add lots of info that serves the same function but is variable depending on the desires of the user.
## How do you add to a collection of sub-documents? What about editing them?
First use the findOne function to find the document, second get the array you need, third add/change the info you need. Finally, you should save it in the array.
You can also use the push method to add items into the collection.


Link: https://john87barker.github.io/final-frontier/