# browser-wallet-generator
This is a client-side Bitcoin wallet generator that runs entirely in the browser.

## Build Commands
- Open the HTML file directly in a browser: `browser-wallet-generator.html`
- For local testing: `python -m http.server` (then navigate to localhost:8000)

## Code Style Guidelines
- **HTML**: Use 4 spaces for indentation
- **CSS**: Follow BEM naming convention for classes
- **JavaScript**:
  - Use camelCase for variables and functions
  - Use PascalCase for constructor functions
  - Prefer async/await over Promises where possible
  - Add clear error handling with try/catch blocks
  - Document complex algorithms with comments
  - Functions should have clear, single responsibility
  - Keep function length under 30 lines where possible
  - Use modern ES6+ syntax (arrow functions, template literals)
  - Always handle errors in asynchronous operations

## Security Guidelines
- Never transmit private keys or sensitive data
- Use native browser crypto APIs when available
- Keep dependencies to a minimum
- Validate all user inputs
