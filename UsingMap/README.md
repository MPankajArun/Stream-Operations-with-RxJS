## Using map() to transform data
Using map() on an Observable is identical to using it on an array. It:

1. Accepts a callback as an argument;
2. Executes it on every element of the array you called it on; and
3. Returns a new array with each element of the original array replaced with the result of calling the callback on it.

The only differences when using map() on Observables are that:

1. Instead of returning a new array, it returns a new Observable; and
2. It executes every time the Observable emits a new item, instead of immediately and all at once.

We can use map() to transform our stream of user data into just a list of their website names: