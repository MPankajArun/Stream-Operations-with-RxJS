## Using switch()
Often, we want to listen to an Observable emitting Observables, but only pay attention to the latest emission from the source.

To extend the Facebook Messenger analogy further, switch() is the case where you . . . Well, switch who you respond to, based on who’s currently sending messages.

For this, RxJS provides switch.

User interfaces furnish several good use cases for switch(). If our app fires off a request every time a user selects what they want to search for, we can assume they only want to see results from the latest selection. So, we use switch() to listen to only the result from the latest selection.

While we’re at it, we should make sure not to waste bandwitdh by only hitting the server for the last selection a user makes every second. The function we use for this is called debounce()

If you want to go in the other direction, and only honor the first selection, you’d use throttle(). It has the same API, but opposite behavior.

