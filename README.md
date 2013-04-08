WordPress Codebird
======================

*Contributors: @automattic, @batmoo, @danielbachuber, @nickdaugherty*
*Tested up to: 3.5.1*
*Stable tag: 1.0.1*
*License: GPLv2 or later*
*License URI: http://www.gnu.org/licenses/gpl-2.0.html*

Description
-----------------------

An extension of the Codebird class to use WordPress' HTTP API instead of cURL.

Provides a drop in replacement for Codebird (mynetx/codebird-php) with improved WordPress integration by replacing all cURL calls with WordPress HTTP API calls.

Usage
--------------------

Include both the Codebird library and `class-wp-codebird.php`, then get a new instance of `WP_Codebird`:

    $wp_codebird = WP_Codebird::getInstance();

The rest of the api is identical to Codebird - it is a drop in replacement that does not require any modification to existing code.