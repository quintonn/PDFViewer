### Plugin's Purpose
The purpose of the plugin is to create a cordova plugin from http://randymcmillan.github.com/PDFViewer with a little bit of code updates taken from https://github.com/sitewaerts/cordova-plugin-document-viewer and https://github.com/vfr/Reader

## Supported Platforms ##

* iOS 7+
* Cordova/Phonegap >=4.0.0

## Installation ##

```bash
cordova plugin add https://github.com/cdibened/PDFViewer.git
```

## Removal ##

```bash
cordova plugin rm cordova-plugin-pdf-viewer
```

## Using the plugin ##

The plugin creates the global object ```PDFViewer``` in the window scope.

### Open a Document File ###

```js
PDFViewr.openPDF(
    url, mimeType, options, onShow, onClose, onMissingApp, onError);
```



