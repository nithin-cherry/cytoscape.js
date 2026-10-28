# Core Architecture Guidelines

This directory contains headless graph math, elements, styling logic, and traversal algorithms.

## Rules
- **No DOM Access**: Code must run in a pure Node.js environment. Do not use `window`, `document`, or Canvas APIs.
- **Separation of Concerns**: Do not calculate rendering bounding boxes or draw elements here.
- **Testing**: Run `npm run test:modules` for internal logic and `npm run test:js` for syntax/linting.