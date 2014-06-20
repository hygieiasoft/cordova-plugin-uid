# org.hygieiasoft.cordova.uid
Cordova plugin to get unique identifiers: UUID, IMEI, IMSI, ICCID and MAC.

This plugin defines a `cordova.plugins.uid` object.
The object is not available until after the `deviceready` event.

		document.addEventListener('deviceready', onDeviceReady, false);
		function onDeviceReady() {
			console.log(cordova.plugins.uid.IMEI);
		}

## Installation
		cordova plugin add org.hygieiasoft.cordova.uid

## Properties
- uid.UUID
- uid.IMEI
- uid.IMSI
- uid.ICCID
- uid.IMSI

## uid.UUID
The `uid.UUID` gets the device's Universally Unique Identifier ([UUID](http://en.wikipedia.org/wiki/Universally_Unique_Identifier)).

		var string = cordova.plugins.uid.UUID;

### Supported Platforms
- Android

## uid.IMEI
The `uid.IMEI` gets the device's International Mobile Station Equipment Identity ([IMEI](http://en.wikipedia.org/wiki/International_Mobile_Station_Equipment_Identity)).

		var string = cordova.plugins.uid.IMEI;

### Supported Platforms
- Android

## uid.IMSI
The `uid.IMSI` gets the device's International mobile Subscriber Identity ([IMSI](http://en.wikipedia.org/wiki/International_mobile_subscriber_identity)).

		var string = cordova.plugins.uid.IMSI;

### Supported Platforms
- Android

## uid.ICCID
The `uid.ICCID` gets the sim's Integrated Circuit Card Identifier ([ICCID](http://en.wikipedia.org/wiki/Subscriber_identity_module#ICCID)).

		var string = cordova.plugins.uid.ICCID;

### Supported Platforms
- Android

## uid.MAC
The `uid.MAC` gets the Media Access Control address ([MAC](http://en.wikipedia.org/wiki/MAC_address)).

		var string = cordova.plugins.uid.MAC;

### Supported Platforms
- Android
