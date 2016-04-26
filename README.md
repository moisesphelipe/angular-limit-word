# limit-word-angular
This is a simple filter to limit words in angular

## Installation
You can install this package with npm or clone the repository

### npm

```shell
npm install angular-limit-word
```

### github

```shell
git clone https://github.com/moisesphelipe/angular-limit-word
```

Then add a `<script>` to your `index.html`:

```html
<script src="/node_modules/angular-limit-word/limitWordFilter.js"></script>
```

# Using in your app
```
{{article.title | limitWord : 8 : '[...]'}}
```
By default the `limitWord` is 8 and the `moreChar` is "[...]" if you like this settings you do not need to specify those like so.
```
{{article.title | limitWord}}
```
it will work the same way.
