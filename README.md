WordPress plugin and open source Android application to track and display your journeys

The WordPress plugin extends the [WordPress XML-RPC](http://codex.wordpress.org/XML-RPC_Support "WordPress XML-RPC") protocol
to enable the belonging Android application to create posts and
to attach and update [GPX](http://www.topografix.com/gpx.asp "GPX") files.

The [Android application](https://github.com/M66B/BackPackTrack "BackPackTrack for Android") will periodically turn on the GPS of your device and acquire and record your position.
You can make waypoints on important locations,
which you can optionally [reverse geocode](http://en.wikipedia.org/wiki/Reverse_geocoding "reverse geocode") when you have an internet connection.

During or after your journey, you can create and upload a GPX file to your WordPress weblog.
The first upload creates a *draft* post with the title of your journey and a hyperlink to the generated GPX file.
Subsequent uploads will only update the GPX file.

The GPX file can be displayed as a map using the [XML Google Maps](http://wordpress.org/extend/plugins/xml-google-maps/ "XML Google Maps") WordPress plugin.

The Android application is designed for low power and offline use.
If you want to continuously track your position, you can better use [My Tracks](http://mytracks.appspot.com/ "My Tracks"),
although this application doesn't have an option to upload GPX files to your weblog.