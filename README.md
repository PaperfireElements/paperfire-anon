# \<paperfire-anon\>

an element to help manage anonymous authentication

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://beta.webcomponents.org/element/paperfireElements/paperfire-anon)

##Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../polymerfire/firebase-app.html">
    <link rel="import" href="paperfire-anon.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<!-- use firebase-app from polymerfire to initialize app -->
<firebase-app
  id="app"
  auth-domain="paperfireelements.firebaseapp.com"
  database-url="https://paperfireelements.firebaseio.com/"
  storage-bucket:
  "paperfireelements.appspot.com"
  api-key="AIzaSyBV90mRwJOGY7uO_RVWkchk9oUBx2E-sac"
  messagingSender-id="637337808974"></firebase-app>
<paperfire-anon is-anonymous="{{isAnon}}" debug>...</paperfire-anon>
```
## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```


## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
