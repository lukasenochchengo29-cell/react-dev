# React Practice

A collection of small React exercises built while learning JSX, components, props, state, events, and rendering lists. The examples run directly in the browser and use CDN scripts, so there is no npm project or build step yet.

## Examples

- `react-basics.html` - A shopping-style page with a product list, cart counter, Add to Cart buttons, and a clock updated with `useEffect`.
- `react-basics2.html` - The same state and list example with separate `Greetings` and `LoginForm` components.
- `chatbot.html` - A simple chat interface demonstrating component props, controlled input, state updates, conditional images, and rendering messages with `.map()`.
- `sandbox1.html` - A packing list that passes `name` and `isPacked` props to an `Item` component and uses conditional rendering.
- `sandbox.html` - A todo list example using JSX, inline styles, imported React modules, and `StrictMode`.
- `app.js`, `data.js`, `utils.js` - A module-based list example that imports people data, builds list items with `.map()`, uses stable keys, and creates image URLs from each person's data.

The repository also contains saved React documentation material in `Passing Props to a Component – React.htm` and its accompanying folder.

## Concepts covered

- JSX expressions and rendering components
- Function components and passing props
- Conditional rendering
- Rendering arrays with `.map()` and using `key` props
- `useState` for interactive values
- Event handlers and controlled inputs
- `useEffect` with cleanup for a repeating timer
- ES module imports and exports

## Running the examples

Open any HTML example in a browser. A local server is recommended because some examples use modules and external resources:

```bash
python3 -m http.server 8000
```

Then visit the example you want, for example:

```text
http://localhost:8000/react-basics.html
```

The examples load React, ReactDOM, Babel, and Day.js from public CDNs. An internet connection is needed when loading them for the first time.

## Notes

These are learning exercises rather than a production application. The chatbot currently uses sample messages, logs the input, and adds a test message; it does not connect to a real chatbot service.
