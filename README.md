# RealtimeTaxiAndroidDemo

This demo showcases PubNub's Publish Subscribe feature. Through this setup, developers can easily create a real time map in a use case such as that of Lyft and Uber. 
https://youtu.be/u9W3ZNHzdN0

Quickstart:

1. In order to set up PubNub in your android app, you will need to create a PubNub app in the PubNub Admin Dashboard (it’s free). Upon creating the app, you will be assigned a subscribe key and publish key. You will need to go to the Constants.java class and enter these credentials where it says INSERT_SUBSCRIBE_KEY and INSERT_PUBLISH_KEY respectively.

2. Now, we must set up our Google Maps API key, so that we can use it in our application. In order to do this head over to Google’s Developer API console. Here, we will create a new project and then generate an API key. Once you have the API Key, enter it in the Android Manifest file, where it says INSERT_API_KEY.

3. Ensure that you have downloaded Google Play Services in your Android SDK Manager, accessible from the tool bar at the top of Android Studio. 

Required Gradle Dependencies:

``` 
implementation group: 'com.pubnub', name: 'pubnub-gson', version: '4.12.0'

implementation 'com.google.android.gms:play-services-maps:15.0.1'

implementation "com.google.android.gms:play-services-location:15.0.1"

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-core', version: '2.9.2'

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-annotations', version: '2.9.2'

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-databind', version: '2.9.2'
```




