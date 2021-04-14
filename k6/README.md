# k6

> Docs: https://github.com/k6io/k6

## Installation

```shell
$ brew install k6
```

## Usage

```js
import http from "k6/http";

export default function () {
  let response = http.get("https://google.com");
}
```

## Testing

```shell
$ k6 run --vus 100 --duration 1s script.js
```
