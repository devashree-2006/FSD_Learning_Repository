# Week 3 – JavaScript Session 2
**Topics:** Callbacks, Event Loop, async/await, Fetch, Closures, and Modules

### 1. Call Stack & Event Loop
- JavaScript is single-threaded.
- The Event Loop handles asynchronous tasks.
- Infinite loops block execution and make the page unresponsive.

### 2. Async/Await
- `await` pauses only the async function, not the entire program.
- Other code continues running while waiting.

### 3. Fetch & Race Conditions
- Fetch requests may finish in a different order.
- Use `AbortController` or request IDs to handle old responses.
- Debouncing reduces unnecessary requests.

### 4. Closures
- A closure remembers variables from its outer function.
- Each function call can have its own private variables.

### 5. JavaScript Modules
- `import` and `export` help organise and reuse code.
- Modules keep code clean and manageable.
