[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/lordoftheflies/plutonium-socket)


# \<plutonium-socket\>

Websocket client.

## Installation

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

```shell
bower install --save lordoftheflies/plutonium-socket
```

## Usage

```html

<plutonium-socket 
    id="socket" 
    protocol="wss" 
    host="echo.websocket.org" 
    auto-start>
    
</plutonium-socket>

```

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="plutonium-socket.html">
    
  </template>
</custom-element-demo>
```
-->
```html

<plutonium-socket 
    id="socket" 
    protocol="wss" 
    host="echo.websocket.org" 
    auto-start>
    
</plutonium-socket>
```


## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

------------

