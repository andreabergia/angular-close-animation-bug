This project is a minimal example of an issue about angular animations.

The component used is a simple "collapsible box", i.e. an accordion. We want to animate
its opening and closing, but with angular 7.2.8+ this doesn't work correctly:

- in Chrome and Firefox only the "opening" animation works; the closing doesn't
- furthermore, in IE and Edge, once the box has been closed, it cannot be reopened again.

The same code works with angular 7.2.7 and below.
