# iSign
## Democratising iBeacons

iBeacons are already in retail for major brands, but following Apples usage guidelines ultimately limits their impact. Apple's vision for iBeacons is focused on larger brands and results in a model where one iBeacon UUID ==> One App ==> One Brand.

While iBeacon deployments are limited to larege brands, the user experience is good. Baut as iBeacon deployment number scale users are faced with having to install hundreds, if not thousands, of Apps to engage with retailers.

If users are dedicated enough to install a large number of iBeacon enabled Apps, they are then faced with a torrent of unsolicited notifications any time they pass by one of their App retailers.

Smaller retailers will find the cost of developing and marketing an App is a barrier for them adopting this technology.

Some companies offer an umbrella model where multiple retailers can sign up to a service that uses just one app.  Competing solutions and household brands wanting full control of their App engagement will perpetuate the App explosion.

Ultimately iBeacon deployment will be limited by the vertical model recommended by Apple.


## Democratising iBeacons

If iBeacons are going to scale and alternative model is needed that meets these three requirements:

  1. Consumers should have control over when they are engaged and what type of engagements they get.
  2. Smaller brands and retailers should be able to deploy and use iBeacons at very low total cost.
  3. Houshold brands should still be able to engage directly with consumers.

iSign leverages standard iBeacons hardware, but uses a different engagement model that aims to deliver the three requirements above.

### Giving control to the consumer

The first step in giving control the consumer is to start with a disire or need led model.

iSign assigns an iBeacon UUID to a subject-of-interest.

A user enters a subject of interest e.g. "Food", this is hashed to generate the 128bit iBeacon UUID.

With this one step iBeacon's are democratised, all food retailers can now advertise their service, using a common UUID that any App can lookup.

iSign combines the iBeacon major/minor values into a single 32bit service provider (retailer) ID.

This retailer ID can be looked up in a database to retrieve the retailer details.

This approach results is a model where one iBeacon UUID ==> subject-of-interest ==> many service providers.

### Integrating with the Apple model of iBeacons

iSign is not trying to compete with iBeacons, it is complimentry, when a retialers details are retrieved from the datbase, these may contain custom URL's that can be used to launch a retailer mobile App.

In this way iSign acts as an iBeacon search portal, that hands off to a retailers vertical App if the user wishes to. But iSign also puts control in the hands of the user, to engage with iBeacon advertisments based on need, rather than on unsolcited push advertisemnts.




