# Changelog for the Mapbox location layer plugin

Mapbox welcomes participation and contributions from everyone.

### 0.5.0-beta.1 - March 29, 2018
- Update Map SDK to 6.0.0-beta.4 [#384](https://github.com/mapbox/mapbox-plugins-android/pull/384)
- Added Camera and tracking modes [#294](https://github.com/mapbox/mapbox-plugins-android/pull/294)
- Added Location layer `onLongClickListener` [#313](https://github.com/mapbox/mapbox-plugins-android/pull/313)
- Add padding APIs to LocationLayerOptions [#313](https://github.com/mapbox/mapbox-plugins-android/pull/313)
- Improved enabling/disabling layers [#308](https://github.com/mapbox/mapbox-plugins-android/pull/308)
- LocationEngine listens to updates after resetting [#307](https://github.com/mapbox/mapbox-plugins-android/pull/307)
- Add ProGuard consumer rules file [#373](https://github.com/mapbox/mapbox-plugins-android/pull/373)
- Fixed icon elevation still showing even when set to zero in some cases [#356](https://github.com/mapbox/mapbox-plugins-android/pull/356)
- Location layer accuracy visibility issue fix [#306](https://github.com/mapbox/mapbox-plugins-android/pull/306)

### 0.4.0 - February 26, 2018
- LocationLayerOptions class added allowing dynamic styling of layer [#267](https://github.com/mapbox/mapbox-plugins-android/pull/267)
- Stale location mode added [#264](https://github.com/mapbox/mapbox-plugins-android/pull/264)
- Assets have be updated and added a 3D effect [#245](https://github.com/mapbox/mapbox-plugins-android/pull/245)
- All assets and attributes are now prefixed [#263](https://github.com/mapbox/mapbox-plugins-android/pull/263)
- Fixed issue with accuracy ring being initialized with value greater than zero [#245](https://github.com/mapbox/mapbox-plugins-android/pull/245)
- `lastLocation()` now returns the location variable directly [#245](https://github.com/mapbox/mapbox-plugins-android/pull/245)
- Replacing LocationEngine now updates the listener to use the new engine [#292](https://github.com/mapbox/mapbox-plugins-android/pull/292)
- Cancel animation as part of stopping the animation [#247](https://github.com/mapbox/mapbox-plugins-android/pull/247)


### 0.3.0 - December 22, 2017
- Change accuracy ring from fill layer to a circle layer [#186](https://github.com/mapbox/mapbox-plugins-android/pull/186)
- Adds last known location API [#199](https://github.com/mapbox/mapbox-plugins-android/pull/199)
- Adds location layer icon click listener [#198](https://github.com/mapbox/mapbox-plugins-android/pull/198)
- Rework location layer abstraction [#196](https://github.com/mapbox/mapbox-plugins-android/pull/196)

### 0.2.0 - August 18, 2017
- Updated Map and Mapbox Java Dependencies [#84](https://github.com/mapbox/mapbox-plugins-android/pull/84)
- Navigation icon now uses runtime styling to scale at lower zoom levels [#84](https://github.com/mapbox/mapbox-plugins-android/pull/84)
- Added listener for compass heading and accuracy changes [#84](https://github.com/mapbox/mapbox-plugins-android/pull/84)

### 0.1.0 - July 17, 2017
- Initial release as a standalone package.
