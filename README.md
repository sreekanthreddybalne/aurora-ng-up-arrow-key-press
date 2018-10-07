auroraNgUpArrowKeyPress
=========================

An AngularJS directive binding input element with Up arrow key press.

## Features
- works similar to `onkeypress="if(event.which==38)"` and `onkeydown="if(event.which==38)"`of Javascript events.
- But with a directive code looks much cleaner.

## Getting started

1. Add a `<script>` tag just after AngularJS framework.
    ```html
    <script src="./angular.min.js"></script>
    <script src="./core/dist/aurora-ng-up-arrow-key-press.js"></script>
    ```

2. Add `auroraNgUpArrowKeyPress` module as a dependency to your application:
   ```javascript
   angular.module('myApp', ['auroraNgUpArrowKeyPress']);
   ```

3. Use directive inside your application:
      ```html
      <input type="text" aurora-ng-up-arrow-key-press="doSomething()" />
      ```
