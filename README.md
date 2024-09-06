![alt-text](images/azprimary-color700.png "State of Arizona")
# State of Arizona | Arizona Sliver Drupal Module

> [!IMPORTANT]
> All Arizona state government websites and online applications are required to use the state sliver.

> [!NOTE]
> **Drupal Version Support**: 8 | 9

The Arizona Sliver module is to provide a Drupal solution to display the mandated sliver, using resources locally to the Drupal site first and then connecting to a remote location for any overrides at static.az.gov. 

## Installing the Module
> **Requires a "page_top" region and JQuery 3.5.1 (min.) to exist in your theme. If you do not have this region available in theme settings, provide one or connect with Agency Platform to collaborate on adding another region option to the code base or to get help on adding the appropriate region to your theme.**
### Method: Composer
1. In the composer project, run `composer require 'State-of-Arizona/az_site_sliver:^1.1'`

### Method: Manual/SFTP
_Please note, this method will require you to return periodically for updates, if any are made._
1. Download the zip file from Code > Download Zip.
2. Extract it locally.
3. Connect to your site through SFTP or git repository.
4. Add the extracted folder to `web/modules/custom` folder, or where you currently store custom Drupal modules relative to your codebase.
5. Turn on the module at `admin/modules` page.


## FAQ & Common issues
### Where can I submit a bug, issue, or feedback report?
For those part of the OKTA single sign on, create a ticket for [Agency Platform at ServiceNow](https://azdoaprod.servicenowservices.com/esc?id=sc_cat_item&sys_id=3f1dd0320a0a0b99000a53f7604a2ef9). Be sure to mark the category as "Agency Platform Website". Otherwise, connect with the state help desk for further assistance to connecting with the Agency Platform team.
### A recent override was published, but I do not see it reflecting on my website.
Arizona State Government Drupal sites may occasionally hang on to cached appearances locally to a device that is viewing the website. Verify these updates are visible through an incognito or private browser, if so then one of two things should occur if the changes need to show immediately and cannot wait until caches resolve themselves:
1. Clear your site's cache through your host or Drupal administration panel (specifically, theming cache)
2. Request for assistance to clear Cloudflare cache with ADOA/ASET.

## Not using Drupal? Alternative Solutions:
View our [Agency Website/Digital Style Guide](https://showcase.az.gov/resources) found at showcase.az.gov for other methods of getting the sliver to work on your website.
