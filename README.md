# Using Syncano with Fuse Example
Example project which is a rewrite of "[Using Parse with Fuse Example](https://github.com/yupferris/fuse-example-using-parse)". This is a super simple app using [Syncano](https://www.syncano.io) as a backend service, where anyone can simply post text, and anyone else can see that text. All relevant code is in the `MainView.ux` file.

## Setup
You'll need to use your own Syncano app backend with this example. Insert your app's Application ID and instance name into the `api-keys.js` file:
```js
module.exports = {
	accountKey: "APIKEY/ACCOUNTKEY",
	instanceName: "YOUR INSTANCE NAME HERE"
};
```

* Create account at [Syncano](https://syncano.io/)
* [Download Syncano](https://github.com/Syncano/syncano-js/releases) / run `get_syncano.sh`.
* (Update .unoproj and MainView.ux)

Once that's done, you're ready to roll!

## Fuse version
This example was produced with Fuse (beta) v0.22.0.

## License
This code is licensed under the BSD2 license (see LICENSE). 
