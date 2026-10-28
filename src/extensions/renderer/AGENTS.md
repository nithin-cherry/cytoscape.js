# Renderer & Canvas Guidelines

This directory translates graph models into DOM and Canvas 2D visual outputs.

## Rules
- **Canvas Performance**: Batch drawing operations and minimize context state changes (`ctx.save()` / `ctx.restore()`).
- **Event Handling**: Map DOM gestures and events back to core element coordinates.
- **Testing**: Visual regressions require manual testing. Run `npm run watch` to start the dev server and test interactions in the `debug/` pages.   