=== Simple Paid Listings ===
Contributors: mikejolley, jakeom
Requires at least: 4.1
Tested up to: 4.9
Stable tag: 1.3.1
License: GNU General Public License v3.0

Add paid listing functionality. Set a price per listing and take payment via Stripe or PayPal before the listing becomes published.

= Documentation =

Usage instructions for this plugin can be found here: [https://wpjobmanager.com/document/simple-paid-listings/](https://wpjobmanager.com/document/simple-paid-listings/).

= Support Policy =

For support, please visit [https://wpjobmanager.com/support/](https://wpjobmanager.com/support/).

We will not offer support for:

1. Customisations of this plugin or any plugins it relies upon
2. Conflicts with "premium" themes from ThemeForest and similar marketplaces (due to bad practice and not being readily available to test)
3. CSS Styling (this is customisation work)

If you need help with customisation you will need to find and hire a developer capable of making the changes.

== Changelog ==

= 1.3.1 =
* Fixes compatibility with PayPal's updated IPN response.

= 1.3.0 =
* Adds compatibility with WP Job Manager 1.29.0 and requires it for future updates.

= 1.2.2 =
* Updated to use PayPal IPN's new response to charge requests.
* Updated to use Stripe's modified response.

= 1.2.1 =
* Prevent payment when listing cost is forced to 0.

= 1.2.0 =
* Job Manager 1.22.0 support

= 1.1.15 =
* Only enqueue stripe scripts when payment needs to be taken.

= 1.1.14 =
* Load translation files from the WP_LANG directory.
* Updated the updater class.

= 1.1.13 =
* Uninstaller.

= 1.1.12 =
* Fix button text when paid listing disabled.

= 1.1.11 =
* Moved self::get_job_listing_cost() so it can be used to disable paid listing.

= 1.1.10 =
* WP_Job_Manager_Simple_Paid_Listings::get_job_listing_cost() and filter.

= 1.1.9 =
* Reset expirey date during renewal.

= 1.1.8 =
* Fire action when payment is complete.

= 1.1.7 =
* Support renewals.

= 1.1.6 =
* Add slash on end of home_url for IPN response.

= 1.1.5 =
* Hide pending payment jobs from 'all' list

= 1.1.4 =
* Added new updater - This requires a licence key which should be emailed to you after purchase. Past customers (via Gumroad) will also be emailed a key - if you don't recieve one, email me.

= 1.1.3 =
* Pass email to stripe

= 1.1.2 =
* Different method for triggering click events
* wp_job_manager_spl_admin_email filter

= 1.1.1 =
* Fix PayPal headers for upcoming API changes

= 1.1.0 =
* Allow payment from job dashboard. Requires Job Manager 1.1.2.

= 1.0.3 =
* Fixed issue where expirey date was not set on new submissions

= 1.0.0 =
* First release.
