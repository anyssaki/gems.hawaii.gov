# gems.hawaii.gov
Temporary developer environment

## Current Situation
The WordPress admin page is displaying numerous red flags concerning outdates in WordPress, plugins, and PHP version.  
One particularly cocerning alert reads:
Your site is running an outdated, insecure version of PHP (5.3.3), which could be putting your site at risk for being hacked.
WordPress will stop supporting your PHP version in April 2019.  Updating PHP only takes a few minutes and will make your website significantly faster and more secure.

When I tried installing the packaged site to Docker, the website cannot support an upgraded PHP version so this dev environment will serve two purposes.
The first is to provide a back-up WordPress site (likely a template) and the second is to try upgrading and testing the current site.
