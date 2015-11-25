# Ecwid bug bounty program.

## Eligibility.

The scope of the whitehat program is limited to Ecwid shops, their admin and their API. This means your whitehat development shop hosted at [your-shop].ecwid.com

Reports on the following classes of vulnerability are eligible for reward, unless they are excluded (see the next section). In most cases, we will only reward the type of vulnerabilities that are listed below.

* Arbitrary code execution.
* SQL injection.
* Privilege escalation to shop owner (from unauthenticated user, customer, or installed app).
* Authentication bypass for login to my.ecwid.com/cp .
* Circumvention of permission model for apps or admin users.
* Cross-site request forgery.
* Cross-site scripting - See the next section for limitations.

## Known issues or previously reported vulnerabilities.

The following reports are not considered as vulnerabilities or are not subject of this bug bountry program.
Please do not report any of the following issues.

* Any issue where a store administrator is able to insert javascript in the storefront area of their own store, including the checkout pages.
* Any issue related to the storefront area being displayed in a \<iframe\> element in the admin area.
* Any issue related to execution of javascript in the Rich Text Editor (for example, when editing the description of a product).
* Arbitrary file upload to the Ecwid CDN.
* CSRF access to modify cart.
* Insecure cookie handling for non-sensitive cookies.
* CSRF for Login, Logout and Signup pages.
* Password reset tokens don’t expire when changing email address.
* Tab nabbing.
* Issues with the SPF, DKIM or DMARC records on Ecwid.com or other Ecwid domains (sometimes reported as email spoofing).
* Mail system abuse.
* XSS that requires full control of a http header, such as Referer, Host, etc.
* User enumeration.
* There's no "X-Content-Type-Options" HTTP header with nosniff value, which can lead to Content Sniffing.

## Ineligible vulnerability types.

Ecwid does not consider the following to be eligible vulnerabilities under this program:

* Denial of Service
* Social Engineering, including phishing
* Vulnerabilities in other Ecwid Inc. web sites or applications
* Failure to implement security best practices such as rate limiting, minimum password strength, and mobile binary protection
* Some server configuration issues
* Any issue in a mobile application that can only be exploited on a rooted or jailbroken device, that depends on physical access to the device or debug access being enabled, or that depends on a vulnerability in the operating system.
* Architectural decisions knowingly made by Ecwid are not considered as valid submissions to the whitehat program even if there may be a more secure alternative configuration. For example, reporting that www.ecwid.com is not using the https protocol will fall in this category. In general, issues that fall in this category will be rejected if we do not plan to implement a fix for them.

## Rules for participation.

The following rules must be followed in order for any rewards to be paid:

* You may only test against shops you have created.
* You must not attempt to gain access to, or interact with, any shops other than those created by you.
* Rules for reporting must be followed.
* Allow a reasonable amount of time for Ecwid to respond to your vulnerability report before publishing details of your exploit.

## Contact

For submission please contact us at whitehat AT ecwid.com
