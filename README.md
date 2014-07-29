launchnativeapp
===============

Launch the native app from phonegap plugin

This plugin allow you to open external application in Android via JavaScript code using package name.

### Usage

Usage is easy as a pie:

```javascript 
window.OpenApplication("com.package.name"); 


No that this should be called after *deviceready* is fired, for example:
```javascript
var openFn = function() {
   window.OpenApplication(app_package);
};
document.addEventListener('deviceready', openFn, false);
```

### Instalation
```
```

### Licence

Released under Apache License 2.0.

