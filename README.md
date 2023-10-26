# swiftrift-login

### Development Setup

```sh
$ npm install
$ npx tailwindcss init
$ npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

After you have the `dist/output.css` file you can use it in your HTML file.

```html
<!-- ./src/index.html -->
<link href="../dist/output.css" rel="stylesheet">
```