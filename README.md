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

1. Update the version, commit it, and tag it (all of these things will happen with the following command):

```
yarn version [<new version> | major | minor | patch]
```

2. `git push upstream master --tags` this adds a new release to the github tags.

3. Open https://github.com/namely/namely-ui-css/releases and click Edit on the right hand side of the "Latest Release".
For the release description add relevant commit messages.

4. Publish updated module:
```
yarn publish
```
