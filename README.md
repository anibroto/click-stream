# click-stream

we will build click-stream processor application, that consumes "like" events, displays how many times an item was "liked". Count of likes is saved in persistent storage. Imagine we only have one item to like, so SQS message doesn't have a payload, and HTTP API returns a single number. Our app will run in ECS.
