=== Boldmapper ===
Contributors: @boldmapper
Donate link: https://boldmapper.com
Tags: store locator, business locations, geocoding, stores, geo, zipcode locator, dealer locator, geocode, google map, location finder, map tools, shop locator, mapbox
Requires at least: 3.0.1
Tested up to: 5.8
Stable tag: 2.0.5
License: LGPL-3.0+
License URI: https://www.gnu.org/licenses/lgpl-3.0.html

Boldmapper's Store Locator is an easy way to add a product locator to your application. Product locators are useful for pointing your customers to where they can find your product in stores. They are great for mapping distributors,
resturant locations, or even food trucks.

== Description ==

With Boldmapper, you can build and manage a store locator for your application. All locations are managed via our web interface at [https://boldmapper.com](https://boldmapper.com). You can easily import existing locations, manually add new ones, track store hours, add tag filters and custom attributes all in one place.

This plugin adds a Boldmapper shortcode and widget so you can integrate your map easily on any page.

= Features =
* Customize your map with themes and CSS.
* Easily import your existing locations with our import wizard.
* Realtime sync your inventory and locations directly from your [Square Store](https://squareup.com/us/en).
* Choose from 6 marker shapes and the color of your choice, or upload your own custom markers.
* Driving distance in km or miles.
* Automatic translation for Arabic, Chinese, French, German, Hindi, Japanese, Portuguese, and Spanish. More languages to come.
* Shortcode to quickly embed the map on your page.
* Set the default location of the map on load.
* Add custom location attributes and tags to filter by, like "Free-Wifi", etc.
* Link to Google Maps driving directions.
* Powerful anonymous analytics to figure out what your users are searching for and where.
* Show store hours for each location and filter by "Open Now".
* Powerful location-aware autocomplete search.
* Whitelabel upgrade options.
* Priority support.
* Manage multiple maps from one easy to use dashboard.

[Check out the Demo](https://boldmapper.com/#demo)


== Installation ==

Installation should take only a few minutes.

1. Upload the `boldmapper` plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. You can now access the Boldmapper admin panel under `Settings -> Boldmapper`. From there, you can
add a global default Map ID from the [dashboard](https://boldmapper.com/dashboard). You can find your Map ID on the
General Settings tab for your map.

### Using the shortcode
Once your Map ID is added you can then use the `[boldmapper]` shortcode on any page to render a map. If you
have multiple maps and would like to specify a different map, you can override the global Map ID by specifying
it in the shortcode like `[boldmapper map="89fb1f31-b36f-4d98-9dc4-90e7dd92a2ad"]`.

### Using the widget
Widget availability will be based on your theme, but wherever you can add a widget you can select the Boldmapper
widget by clicking on `Add a Widget` and selecting `Boldmapper Store Locator`.

== Frequently Asked Questions ==

= What is the Mapbox API Token? =

For your map to render, you will need to register for a [Mapbox](https://mapbox.com) API token.  Once registered, you can find your token in the [https://account.mapbox.com/access-tokens/](Mapbox Dashboard).

== Screenshots ==

1. Add images and store hours to your individual locations.
2. Filter location with custom tags.
3. See hot search terms and locations that your visitors are searching from.

== Changelog ==

= 2.0.5 =
* Update readme and more images.

= 2.0.4 =
* Update images.

= 2.0.3 =
* Update icon and readme.

= 2.0.2 =
* Fix supported Wordpress versions.

= 2.0.1 =
* Tested against Wordpress 5.7
* Fix bug with default map ID configured in plugin settings not loading correctly.

= 2.0.0 =
Release new version with branding as Boldmapper

= 1.0.2 =
Update readme with new naming

= 1.0.1 =
Update readme

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.0 =
Initial release
