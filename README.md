# Cookieburra
JS library to share information (local storage and 1st party cookies) across domains.

Used in scenarios where user spans whitelisted partner domains outside of rakuten.co.jp as part of a single “rakuten session”.  For remarketing, personalization, and A/B testing, we want to share information about user to the partner page, but lacked back-end support to share login data status directly.  Cookieburra is two JS libraries, one implemented on the partner (controller) one that sends a request to the library on rakuten.co.jp (receiver) that responds to the request for whitelisted domains and shares the requested info from cookie and local storage data.
