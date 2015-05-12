## Scrollin

Do something great when an element enters the viewport.

```js
Scrollin.track(document.querySelector('#hi'), {handler: () => alert('hi!')})
```

## API

* `Scrollin.track(document.querySelector('#hi'), {handler: () => alert('hi!')})`
* `Scrollin.untrackAll()`
* `Scrollin.untrack(document.querySelector('#hi'))`

### Dev

* `npm i`
* `npm run dev`

#### Building

* `npm run compile`
