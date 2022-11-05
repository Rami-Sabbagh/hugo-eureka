Thank you for investing your time in contributing to Eureka! This is a document that is still under construction and therefore does not cover all considerations during development.

## Setup development environment

- Install node.js dependencies by executing `npm i`.

## CSS Resources

Always remember to update the cached resources in `resources/_gen/` when you make changes to CSS.

When doing so make sure to use production mode.

```
HUGO_ENVIRONMENT === 'production'
```

## Font Awesome

Eureka reduce the size of Font Awesome with tree shaking. If your PR contains changes to Font Awesome icons, please make sure to update `layouts/partials/utils/get-fontawesome-icons.html` to include all related icons.