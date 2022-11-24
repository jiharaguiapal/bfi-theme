# bfi-theme-colors

## Install

```
npm install bfi-colors
```

### Requirements

Note that installing as a dev dependency --save-dev 
or -D will not work correctly.

Make sure to install Sass


### Usage


Create custom.scss file inside your assets folder
Add this lines to your custom.scss
Note that bfi-colors should be imported first before bootstrap

```js live=true
@import "../node_modules/bfi-colors/scss/style";
@import "../node_modules/bootstrap/scss/bootstrap";
```


Download font files used in the repository
This is important for the package to work
[Download Red-Hat-Display here](https://github.com/jiharaguiapal/bfi-theme/tree/main/scss)
After downloading, copy and paste font files inside the assets directory

![assets](https://github.com/jiharaguiapal/bfi-theme/blob/main/scss/assets.png)


Go to nuxt.config.js
Then import custom.scss as global css


```js live=true
css: ["@/assets/custom.scss"],
```
![nuxt](https://github.com/jiharaguiapal/bfi-theme/blob/main/scss/nuxt-add-css.png)

<!-- 
```css live=true

  "bfi-success":#00A651,
  "bfi-danger":#E84D2E,
  "bfi-warning":#FEC006,
  "bfi-edit":#EE8400,
  "bfi-text":#363636,
  "bfi-subtext":#193C2A,
``` -->

### Fonts

Access the customized color variants using the "variant" property
See the list of the custom variant names below

### Color Variants

Access the customized color variants using the "variant" property
See the list of the custom variant names below


### Sample Usage

![snippet](https://github.com/jiharaguiapal/bfi-theme/blob/main/scss/snippet.png)


### Custom Variant Names

![theme-colors](https://github.com/jiharaguiapal/bfi-theme/blob/main/scss/theme-colors.png)

<!-- ### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration -->

<!-- See [Configuration Reference](https://cli.vuejs.org/config/).
"# publish-test"
"# publish-test" -->
