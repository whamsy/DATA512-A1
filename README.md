# DATA512-A1-Data Curation

## Goal

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through September 30 2018, to demonstrate ability to follow best practices for open scientific research in designing and make the project fully reproducible by others: from data collection to data analysis.

## Wikimedia REST API

The WIkimedia Pagecounts API and the Pageviews API are used to collect data. The terms of license can be found at https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions.

The Pagecounts API (https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts) provides access to desktop and mobile traffic data from January 2008 through July 2016.

The Pageviews API (https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through September 2017.

## Final Data File (en-wikipedia_traffic_200801-201709.csv)

The file has the following columns:

year: year of the time stamp associated with the traffic

month: month of the time stamp associated with the traffic

pagecounts_all_views: number of page counts from both desktop and mobile using Pagecounts API
pagecounts_desktop_views: number of desktop page counts obtained using Pagecounts API
pagecounts_mobile_views: number of mobile page views obtainedusing Pagecounts API

pageviews_all_views: number of page views from both desktop and mobile obtained using Pageviews API
pageviews_desktop_views: number of desktop page views obtained using Pageviews API
pageviews_mobile_views: number of mobile page views obtained using Pageviews API

### Data from the PageViews API excludes traffic from web spiders or crawlers, this was done to only consider organic traffic from users.

## Licensing

By using Wikimedia REST API, you agree to Wikimedia's Terms of Use (https://wikimediafoundation.org/wiki/Terms_of_Use/en) and Privacy Policy (https://wikimediafoundation.org/wiki/Privacy_policy)

This project is licensed under the MIT License.



