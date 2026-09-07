# Ocasio Admin Username Changer

> Lightweight WordPress plugin to safely change your WordPress username and harden security without database scripts or session dropouts.

## Overview

WordPress permanently locks the username field in user profiles. **Ocasio Admin Username Changer** unlocks this limitation, allowing site owners and administrators to safely change their login username directly within the dashboard.

## Features

* **Direct Database Update:** Safely updates the `user_login` column in the database without raw SQL scripts.
* **Instant Session Refresh:** Cleans user cache and refreshes authentication cookies so you stay logged in without interruption.
* **Input Validation:** Prevents illegal characters, spaces, empty strings, and duplicate usernames.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript loaded on public pages.
* **Ocasio Suite Integration:** Managed directly under **Ocasio Plugins -> Username Changer** or through the central suite dashboard.

## Installation

1. Download the latest `ocasio-admin-username-changer.zip` file from [Releases](https://github.com/kevinocasio/ocasio-admin-username-changer/releases).
2. In your WordPress admin dashboard, navigate to **Plugins -> Add New Plugin -> Upload Plugin**.
3. Choose the downloaded `.zip` file and click **Install Now**.
4. Click **Activate Plugin**.
5. Access your settings under **Ocasio Plugins -> Username Changer** in your sidebar.

---

## Author & Resources

* **Author:** [Kevin Ocasio](https://kevinocasio.com/)
* **Plugin Page:** [Ocasio Admin Username Changer on KevinOcasio.com](https://kevinocasio.com/wordpress-plugins/ocasio-admin-username-changer/)
* **WordPress Plugins:** [Free WordPress Plugin Directory](https://kevinocasio.com/wordpress-plugins/)
* **Software Portfolio:** [Live Projects & Digital Assets](https://kevinocasio.com/portfolio/)
* **Tools & Resources:** [Recommended Tech Stack & Tools](https://kevinocasio.com/tools/)
* **License:** GPL-2.0-or-later
