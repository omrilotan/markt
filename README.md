# markt [![](https://nodei.co/npm/markt.png?compact=true)](https://www.npmjs.com/package/markt) [<img src="https://assets-cdn.github.com/pinned-octocat.svg" style="height:.75em">](https://github.com/omrilotan/markt)

## CI-CD use

```sh
npx markt README.md ./docs/index.html ./scripts/docs.template.html
```

#### arguments

| Order | Role | Default
| --- | --- | ---
| 1 | Source | `./README.md`
| 2 | Destination | `./index.html`
| 3 | Template | None

## Template is optional

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
        <title>My document</title>
        <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=yes">
        <link rel="stylesheet" href="https://omrilotan.github.io/markt/styles.css">
    </head>
    <body>
        {{ content }}
    </body>
</html>
```
