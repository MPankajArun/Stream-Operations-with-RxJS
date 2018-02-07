## Combining streams with concat() and merge()
Often, we’ll have multiple streams that we need to put together. There are many ways to combine streams, but there are a few that come up more than others.

Concatenation and merging are two of the most common ways to combine streams.

Concatenation creates a new stream by emitting the values of a first stream until it completes, and then emitting the values of a second stream.

Merging creates a new stream from many streams by emitting values from whichever stream is active

Think of talking to two people at once on Facebook Messenger. concat() is the scenario where you get messages from both, but finish your conversation with one person before responding to the other. merge() is like creating a group chat and receiving both streams of messages simultaneously.