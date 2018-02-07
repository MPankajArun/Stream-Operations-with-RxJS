## Limiting results with take()

take() and takeWhile() round out the basic functions on simple streams.

take(n) reads n values from a stream, and then unsubscribes.

We can use scan() to emit the our object every time we receive a website, and only take() the first two values.