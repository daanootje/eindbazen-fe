# \<eindbazen-fe\>



## Install the Polymer-CLI
1 - [Install npm](https://www.npmjs.com/get-npm)
2 - [Install bower](https://bower.io/)
3 - [Install polymer](https://www.polymer-project.org/2.0/start/install-2-0)
 
First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Building your package

```
$ bower install
```
or
```
$ bower install [package]
```

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

https://github.com/akveo/polymer-admin

Development workflow
Run development web-server:

gulp serve
Run production web-server:

gulp serve:dist
