=== Ocasio Admin Username Changer ===
Contributors: ocas
Tags: change username, admin username, username changer, user security, login handle
Requires at least: 6.0
Tested up to: 7.1
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Safely change your WordPress username to harden security or update your login handle without database scripts.

== Description ==

WordPress permanently locks your username on the user profile screen, displaying "Usernames cannot be changed." If you set up your site with a generic username like `admin` or want to update your login handle, you're stuck unless you run raw SQL queries in phpMyAdmin.

Using generic usernames makes your website an easy target for automated brute-force attacks. Hackers test common usernames millions of times every day.

Ocasio Admin Username Changer unlocks this limitation safely. It lets administrators update their login username directly from the WordPress dashboard in one click. The plugin safely updates your user record in the database, refreshes your active login session, and keeps you logged in without any session dropouts.

= Features =

* **Safe Username Updates:** Change any administrator username directly in the database without SQL scripts.
* **Instant Session Refresh:** Automatically updates your authentication cookies so you don't get logged out.
* **Built-In Input Validation:** Checks for illegal characters, spaces, and duplicate usernames before saving.
* **Zero Front-End Code:** Runs entirely in the WordPress admin with 0 bytes of extra CSS or JavaScript loaded on public pages.
* **Clean Single-Card Screen:** Centered, distraction-free control panel inside your WordPress dashboard.

== Installation ==

1. Upload the `ocasio-admin-username-changer` folder to your `/wp-content/plugins/` directory, or install the zip file directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Open **Ocasio Plugins -> Username Changer** in your sidebar to change your username.

== Frequently Asked Questions ==

= Will changing my username break my authored posts? =
No. WordPress tracks authored posts by your internal User ID number, not your text username. All your posts, pages, and media attachments remain linked to your account.

= Will I be logged out when I change my username? =
No. The plugin automatically refreshes your WordPress login cookies in the background so you stay logged into your dashboard.

= Can I deactivate the plugin after changing my username? =
Yes. The username change is written directly to the WordPress users database table. You can keep the plugin active for future changes or deactivate it whenever you want.

== Changelog ==

= 1.0.0 =
* Initial public release.
