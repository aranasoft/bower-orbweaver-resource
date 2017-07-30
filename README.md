# packaged orbweaver-resource

This repository is for `npm` and `bower` distribution. The source for this module is in the
[Orbweaver sourcecode](https://github.com/aranasoft/orbweaver/tree/master/src/) repository.
Please file issues and pull requests against that repository.

## Install

You can install this package either with `npm` or with `bower`.

### npm

```shell
npm install orbweaver-resource
```

Then add `orbResource` as a dependency for your app:

```javascript
angular.module('myApp', [require('orbweaver-resource')]);
```

### bower

```shell
bower install orbweaver-resource
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/orbweaver-resource/orbweaver-resource.js"></script>
```

Then add `orbResource` as a dependency for your app:

```javascript
angular.module('myApp', ['orbResource']);
```

## License

Orbweaver is copyright of Arana Software, released under the [BSD License](http://opensource.org/licenses/BSD-3-Clause).
