# Namely UI CSS

```
yarn install @namely/ui-css
```

# CDN

```html

<!-- get the latest version -->
<link href="https://unpkg.com/@namely/ui-css" rel="stylesheet" type="text/css">

<!-- get minified -->
<link href="https://unpkg.com/@namely/ui-css/css/styles.min.css" rel="stylesheet" type="text/css">

<!-- specify a version -->
<link href="https://unpkg.com/@namely/ui-css@SPECIFY_VERSION/css/styles.min.css" rel="stylesheet" type="text/css">
```

Read more about [https://unpkg.com](https://unpkg.com)

# Usage

For now, wrap your markup in a `.namely-ui` container:
```html
<div class="namely-ui">
  <p class="p2">This text has padding</p>
</div>
```

# Release
For all releases, a maintainer will complete the following steps:

1. Update the version in the package.json, commit it and merge your branch. 

2. In Github go to `Tags` > `Releases` and create a new release with the new version. 

3. In the command line, on the latest pulled down master branch, publish the updated module:
```
yarn publish
```
