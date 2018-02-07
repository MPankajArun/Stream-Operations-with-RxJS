## Collecting results with reduce()
reduce() allows us to use all of our individual values and turn them into a single result.

reduce() tends to be the most confusing of the basic list operations, because, unlike filter() or map(), it behaves differently from use to use.

In general, reduce() takes a collection of values, and turns it into a single data point. In our case, we’ll feed it a stream of website name, and use reduce() to convert that stream into an object that counts how many websites we’ve found, and the sum of the lengths of their names.

Keep in mind that reduce() only returns a result when the source Observable completes. If you want to know the state of the accumulator every time the stream receives a new item, use scan() instead.