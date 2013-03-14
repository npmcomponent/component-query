
# query

  Query the DOM with selector engine fallback support.

## Installation

    $ component install component/query

## API

### query(selector, [el])

  Query `selector` against the document or `el`
  and return a single match.

```js
query('ul > li');
query('ul > li', articles);
```

### query.all(selector, [el])

  Query `selector` against the document or `el`
  and return a all matches.

```js
query.all('ul > li');
query.all('ul > li', articles);
```

## Fallback engines

  Currently supported:

  - [query-zest](https://github.com/component/query-zest)

## License

  MIT