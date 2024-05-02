```bash
npm i node-sass
```

- package.json

```json
"compile:sass" : "node-sass src/sass/main.scss src/css/style.css"
```

- separate to each file, and import them in main.scss, escape the file extension

> main.scss

```scss
@import "abstracts/variables";
@import "abstracts/mixins";
@import "base/animations";
```

> \_variables.scss

```scss
$color-primary: red;
$width-input: 100px;
$height-input: 30px;
```
