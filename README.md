# gems.hawaii.gov
Temporary developer environment

## Current Situation
The WordPress admin page is displaying numerous red flags concerning outdates in WordPress, plugins, and PHP version.  

>Your site is running an outdated, insecure version of PHP (5.3.3), which could be putting your site at risk for being hacked.
>WordPress will stop supporting your PHP version in April 2019.  Updating PHP only takes a few minutes and will make your website >significantly faster and more secure.

When I tried installing the packaged site to Docker, the website cannot support an upgraded PHP version so this dev environment will serve two purposes.
1. Provide a back-up WordPress site
2. Iterate on the current site

### Back-Up WordPress site
The backup site is a WordPress template found on [ColorLib](https://colorlib.com/wp/themes/illdy/).  The resources provided are a [demo site](https://colorlib.com/illdy/) and [theme documentation](https://colorlib.com/wp/support/illdy/).
