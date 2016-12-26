# generator-angular-material [![NPM version][npm-image]][npm-url] [![Dependency Status][daviddm-image]][daviddm-url]
> Google&#39;s Angular Material - in progress

## Installation

First, install [Yeoman](http://yeoman.io) and generator-angular-material using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-angular-material
```

Then generate your new project:

```bash
yo angular-material appName
```

Run server


```bash
gulp | sudo gulp
```


Generate a controller:

```bash
yo angular-material:controller controllerName
```

Adds extension -controller.js to filename and Controller to controllerName

Generate a directive:

```bash
yo angular-material:directive directiveName
```

Adds extension -directive.js to filename and Directive to directiveName


Generate a verbose directive:

```bash
yo angular-material:verbose-directive directiveName
```

Adds extension -directive.js to filename and Directive to directiveName


Generate a factory:

```bash
yo angular-material:factory factoryName
```

Adds extension -factory.js to filename and Factory to factoryName


Generate a service:

```bash
yo angular-material:service serviceName 
```


Adds extension -service.js to filename and Service to serviceName


Generate a component:

```bash
yo angular-material:component componentName path/to/partial 
```

For this to work, each time you inject a component you must specify {{component}} where you would like it to be injected in your partial.

Component list - must use exact name
- autocomplete
- card
- checkbox
- chips
- content
- datepicker
- fab-speed-dial
- fab-toolbar
- grid-list
- list
- menu
- nav-bar
- select
- sidenav
- slider
- tabs
- toolbar


Refer to https://material.angularjs.org/latest/ for how to use these components


All JavaScript/CSS dependencies will be automatically injected into your dev/dist index.html in proper order when running the browsersync server.

All bower components come first. Use bower when installing any new modules and you won't have any issues. Just be sure to inject them in your app module!


## License

MIT © [Google](https://github.com/iansawyerva)


[npm-image]: https://badge.fury.io/js/generator-angular-material.svg
[npm-url]: https://npmjs.org/package/generator-angular-material
[daviddm-image]: https://david-dm.org/iansawyerva/generator-angular-material.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/iansawyerva/generator-angular-material