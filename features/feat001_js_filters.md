# JS Filters

Add abilities for template writers to add own custom JS template filters.

We use already a JS engine for the simulation. We could allow template developers to add a `filters.js` file into their template and load it before generator run. All functions inside then register as filters in the filter map.

```js
function toUpper(s) {
  return String(s).toUpperCase();
}

filters["toUpperJs"] = toUpper;
```

We need to see how we expose our nodes to the JS filters. Also the common str handling we use (e.g. camel, snake) should be exposed to JS.
