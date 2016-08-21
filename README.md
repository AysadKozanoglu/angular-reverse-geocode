angular-reverse-geocode
=======================

AngularJS reverse geocoding directive


###Demo

To see a demo and further details go to https://plnkr.co/edit/kQCsYr

###Installation

Install using bower: `bower install angular-reverse-geocode`

Alternatively download the code and include the angular-reverse-geocode.js file in your page.

Add the 'angularReverseGeocode' directive as a dependency of your AngularJS application:

```javascript
angular.module('myApp', ['angularReverseGeocode']);
```

###Usage

To use add a reverse-geocode tag to your page with attributes containing lat and long coordinates, e.g:

```html
<reverse-geocode lat="40.730885" lng="-73.997383"></reverse-geocode>
```
###with $scpoe or with "controller as vm"
If the GPS coordinates are coming from scope variables set in your AngularJS controller you need to use curly-brace expression bindings, e.g:
```javascript
<reverse-geocode lat="{{vm.model.latitude}}" lng="{{vm.model.longitude}}" />
```
