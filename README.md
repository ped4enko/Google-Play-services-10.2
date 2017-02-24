# Google-Play-services-10.2
Highlights from the Google Play services 10.2 release.

Android version 2.3.x (Gingerbread) Deprecation

Google Play services 10.2.x is the first release that no longer includes full support for Android version 2.3.x (Gingerbread). Apps developed using SDK release 10.2.x and later require a minimum Android API level of 14 and cannot be installed on devices running an API level below 14. To learn more about your options, including building multiple APKs to extend your app's support for Android Gingerbread, see the Android Developers Blog.
Ads

Added support for video assets to Native Advanced content ads and Doubleclick for Publishers (DFP) custom-rendered native ads.
Added the destroy() method to the NativeCustomTemplateAd interface.
Added the getVideoController(), setVideoOptions, and getVideoOptions() methods to the PublisherAdView class.
Added the AdChoicesView class.
Added the getAdChoicesContent() and setAdChoicesContent() methods to the NativeAdMapper class.
Added the InitializableMediationRewardedVideoAdAdapter interface for rewarded video adapters capable of initializing multiple ad units at once.
Smart Lock for Passwords

Improved the behavior of ID tokens with Smart Lock. Apps must now explicitly request a token by calling setIdTokenRequested(true). Also, apps can specify the audience and nonce values for a token using the setServerClientId() and setIdTokenNonce() methods. To learn more, see the following API reference updates:

Added the getAccountTypesSet(), getIdTokenNonce(), getServerClientId(), and isIdTokenRequested() methods to the CredentialRequest class.
Added the setIdTokenRequested() and setServerClientId() methods to the CredentialRequest.Builder class.
Added the getIdTokenNonce(), getServerClientId() and isIdTokenRequested() methods to the HintRequest class.
Added the setIdTokenNonce(), setIdTokenRequested() and setServerClientId() methods to the HintRequest.Builder class.
Awareness

Added Fence API methods to extend the range of time fencing options for developers. To learn more, see TimeFence.aroundTimeInstant() and TimeFence.inTimeInterval().
Added Snapshot API interfaces to get semantic time intervals for the current time and location. To learn more, see SnapshotAPI.getTimeIntervals(), and TimeIntervalsResult() and TimeIntervals() classes.
Google Sign-in

Added the ability for game developers to use the Google Sign-in API to simplify server-side authentication. To learn more, see the GoogleSignInOptionsExtension interface, the GoogleSignInOptions class, and the GoogleSignInOptions.Builder.addExtension() method. To learn more about integrating server-side authentication in your games, see Enabling Server-Side Access to Google Play Games Services.
Google Fit

Added new health data types that let you write a wider variety of health data to the Google Fit platform, including blood pressure, blood glucose, oxygen saturation, body position, body temperature, and reproductive health data. To learn more, see the HealthDataTypes and HealthDataFields classes.
Maps

This release introduces custom styling for polylines and for the outlines of polygons and circles.

You can now store arbitrary data objects with your geometry objects. For example, call setTag() to add a data object to a polyline.
For a full list of features, bug fixes, and other notes, see the release notes for the Maps Android API.
Nearby

Added the AudioBytes class to the Nearby messages.audio API to allow devices to send or receive data using near-ultrasound audio.
Firebase

The latest update to Firebase includes several improvements across multiple features, including Analytics, Authentication, Realtime Database, Storage, Test Lab for Android, Crash Reporting, and Dynamic Links. For more information, see Firebase Android SDK Release Notes.
