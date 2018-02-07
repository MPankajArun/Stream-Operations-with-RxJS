## Operations on Simple Streams
The fundamental functions on simple streams—those that emit simple values, like strings—include:

1. map()
2. filter()
3. reduce()
4. take() / takeWhile()
5. concat() & merge()
6. switch()

With the exception of take() and takeWhile(), these are analogous to JavaScript’s higher-order array functions.

We’ll apply each of these by solving an example problem: Finding all the users in our database who have a .com or .org website, and calculating the average length of their websites’ names.

JSONPlaceholder will be our source of users. Here’s the JSON representation of the user data we’ll be working with.