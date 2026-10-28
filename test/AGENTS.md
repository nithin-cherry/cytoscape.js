# Testing Guidelines

## Test Runner Routing
- Internal logic (`src/core/`): Use Mocha in `test/modules/`.
- Public API changes: Use Mocha in `test/`.
- Browser behavior/UI: Use Playwright in `playwright-tests/`.

## Commands
- Playwright Setup: `npx playwright install --with-deps`
- Rapid Iteration: `npm run test:js` and `npm run test:modules`
- Build/Bundle Testing: `npm run test:build`
- Full CI Run: `npm test` 