![A screenshot of nine pages with charts and tables from the report template](/img/Interactive-Website-Performance-Report-Template-Thumbnail-v-1-2.png)

## Overview

The report template is created for everyone who would like to analyse the performance of a website. It takes data from your site using Google Analytics and displays it in [Google Data Studio](https://datastudio.google.com/), Google's free online tool for visualising a large amount of data to get useful insights. Google Data Studio can load data from all kinds of sources, e.g. Google Analytics, Google Search Console, Google Ads, Facebook and a lot more.

## Versions Ready to Use

### Version 1.2

- [Google Analytics: Standard](https://datastudio.google.com/open/1Jiavzc2nbjqSwVTwD5x5UNKHvI2JDLbd) - for any website that uses Google Analytics
- [Google Analytics: Standard + Blog](https://datastudio.google.com/open/1MYPa8HNdkmAPOxifsimT87I1fWnMdX8n) - for any website that uses Google Analytics and has a blog
- [Google Analytics: Standard + Goals](https://datastudio.google.com/open/1QZ_rwCEUBy-Mf_THaHWvM8pyxksHDqEU) - for any website that uses Google Analytics and has Goals set up in Google Analytics
- Google Analytics: Standard + Ecommerce
- Google Analytics: Standard + Blog + Goals
- [Google Analytics: Standard + Blog + Ecommerce](https://datastudio.google.com/open/1mhFKT-lvu3GJWKTJ2-YxNZrVRg71YMVR) - for any website that uses Google Analytics and has Enhanced Ecommerce set up in Google Analytics
- [Google Analytics: Standard + Blog + Goals + Ecommerce](https://datastudio.google.com/open/1EaReqzhLwPjgKXC4tuYreRKcjGhm_XaV) - for any website that uses Google Analytics and has a blog, Goals and Enhanced Ecommerce set up in Google Analytics

Changelog:

- Added filters: date range, marketing channel, country, device and gender
- Added new content to the following pages: Engagement and Glossary
- Removed page descriptions from all pages
- Added "Prepared with 'heart-icon' by YourCompanyName" in the footer of every page as a small branding accent
- Decreased page side margins
- Creating report variations for specific use cases to avoid showing charts with no data
- Tens of small improvements

### Version 1.1

[Google Analytics: Standard + Blog + Goals + Ecommerce](https://datastudio.google.com/open/1xfWErOo4-xmK8jqVG-74lfMDLeyOfA2q)

Changelog:

- Added pages: Audience, Page Load, Blog, Glossary
- Expanded the Device page
- Temporary removed linkings from the top navigation to avoid confusion when you copy the report and navigation items still linked to the original report
- Tens of small improvements

### Version 1.0

[Google Analytics: Standard + Goals + Ecommerce](https://datastudio.google.com/open/1vNN1hnIoxbxz88Jv7LvO1VF6OZwJ07xW)

Changelog:

- Added pages: Summary, Overview, Channels, Engagement, Devices, Location, Goals, Ecommerce
- Designed theme
- Added navigation with links to jump between pages

## Work in Progress

### Version 1.3

[Google Analytics: Standard + Blog + Goals + Ecommerce + Google Ads](https://datastudio.google.com/open/1tQ6uCHDo7lIpHNnmmPFlHLLpuE9iw3D2)

Changelog:

- Added pages: Ads 1, Ads 2
- Corrected positive and negative colours for all page load and bounce rate scorecards
- Tens of small improvements

## Instructions

1. Log into your Google Data Studio account
   - Log into your Google Data Studio or [create a free account](https://datastudio.google.com/)
2. Selecting a report
   - Click on a link to one of the reports that you would like to use above.
3. Copy the report
   - Move your mouse cursor to the top edge of the report window. The top navigation will appear.
   - On the right-hand side, you will see an icon with two rectangles, one on top of another. Click on it to make a copy of the report.
   - In a pop-up window, select a new Data Source. You can use a "Sample Google Analytics Data" if you would like to just play with the report or click on a drop-down field below heading the "New Data Source". Then click "Create New Data Source" button at the bottom if you would like to use data from one of the sites that you manage. In the search box, type "Google Analytics" and select it. Then press an "Authorize" button, and "Allow" on a page that will appear. Now select a Google Analytics account, then a property, and finally a view of the website for which you would like to use this report. Next press "Connect" button in the top-right corner. Then "Add to Report" button in the top-right corner. Then press "Copy report" button. You can find more information about this step in [Google Analytics data source tutorial](https://support.google.com/datastudio/answer/6295036?hl=en) at the Google Help Center.
   - Give it an appropriate name like "Website Performance Report for Company X - March 2019" by clicking on the text "Website Performance Report..." in the top-right corner.
4. Edit the report
   - If you are not in the "Edit mode". Move your mouse cursor to the top edge of the report window. Top navigation will appear. Then click a grey button that says "Edit". Now, you can change every single thing in this report.
   - Go to "File" (top navigation) > select "Report Settings" > select the date range for which you would like to show the data (to be able to do it, you need first select the report-level data source). Once done, it will be updated on all pages.
   - Remove the "Company's Logo" placeholder. Once removed, it should automatically disappear from all pages. Then add your company's or client's logo by going to Insert (top navigation), then Image. Upload the logo, resize it a place in the top-left corner. Right-click on it, and select "Make report-level". The logo will appear on all pages in this report.
   - Replace "YourCompantName" in the footer with your company name.
   - Update a text field in the top-right corner so that it reflects the month and year from which the data was pulled.
   - If the report includes the "Blog" page, you need to make the following changes: 1. In the section "Session by Authors" you need to edit the table and change dimension "Brands" to "Authors". 2. In the section "Session by Content Categories" you need to edit the table and change dimension "Product Categories" to "Post Categories". 3. Select "Resources" in the top navigation, then "Manage Filters". You will need to edit "Blog Pages" and "Blog as a Starting Point" filters by clicking the "EDIT" buttons. Replace "/google+" with the name of the directory that the blog posts contain in the URL. E.g. if you post URL look like www.example.com/blog/post-name/ enter in the field "/blog/", if it looks like www.example.com/insights/post-name/ enter in the field "/insights/".
5. Optional improvements
   - make page names in the top navigation clickable by adding links to them
   - make titles of pages on a website clickable by creating a calculated filed like HYPERLINK(CONCAT("//mydomain.com", Page), Page Title)
   - Add any branding that you want (e.g. your company logo, contact details, change the used colour, etc.).
6. Check each page
   - Glance through each page to check if you are happy with everything. For some sites, a few charts might not show data. Report an issue on GitHub, and I will try to help you out.
7. Sharing report
   - To share a link to the report with your client or your team, click on an icon of a person with the plus sign beside in the top right-hand corner. Enter an email or a person that you would like to send an invitation to see this report. In the drop-down field on the right-hand side select if you would like to give that person an editor only viewer permission.
   - To save the report as a PDF and send a static version of it to the customer. To do it, go to "File" (top navigation), select "Download as" > select "PDF".
8. Navigating the report
   - To navigate the report use the "right" and "left" arrows on your keyboard to see the next and previous page respectively.

## An Open-Source License

License: MIT license

Permission is hereby granted, free of charge, to any person obtaining a copy of this report template and associated documentation files (the "Report"), to deal in the Report without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Report, and to permit persons to whom the Report is furnished to do so.

## Call for Contributors

If you are interested in making this Google Data Studio report template event better, feel free to contact me. It will be great to join forces with you on this amazing journey to help everyone easily prepare an interactive report template that shows the performance of any website.

## Google Data Studio Courses

1. Free:

   - An official [Google Data Studio Introduction Course](https://analytics.google.com/analytics/academy/course/10) by Google

## Helpful Resources

- [What's new in Google Data Studio](https://support.google.com/datastudio/answer/6311467)
- [A list of functions available for calculated fields](https://support.google.com/datastudio/table/6379764)

## Credits

This report template couldn't be prepared without amazing people who experimented with Google Data Studio before and shared their work with the community.

### Google Analytics Reports

#### Multiple pages

   - [DigitalSasi Web Analytics 3.1](https://datastudio.google.com/reporting/1_TRiGmfJrdR5jdSoX9vV1brQu_THXNae/) by [DataSasi](https://datasasi.com/)
   - [E-commerce Website Analytics Data Studio Report](https://datastudio.google.com/reporting/0BzHxHRjCBXe8WVRMa0tULUJGMm8/) by [Onur SOYLAN](https://www.linkedin.com/in/onursoylan/)
   - [Funnel Visualizer by](https://datastudio.google.com/u/0/reporting/1igHMbckc4tScPBcIX7pmzb1sGAeZHwZz/) by [Click Targeter](https://www.clicktargeter.com/)

#### Overview

   - [GA Audience Overview with Data Control](https://datastudio.google.com/u/0/reporting/0B_U5RNpwhcE6YmJXZ081VG5DSXc/) by Unknown
   - [Monthly Overview](https://datastudio.google.com/u/0/reporting/0B3zl3GIjosRCQTRjdTlNSlNfc3M/) by [Bounteous](https://www.bounteous.com/)
   - [Acquisition EEG](https://datastudio.google.com/u/0/reporting/1apr57Vpe3Jjj10QhJ2YS_QCpwYWkd93C/) by [Joshua Cottrell-Schloemer](https://www.linkedin.com/in/joshcottrell/)

#### SEO

   - [SEO report](https://webris.org/seo-report/) by [Webris](https://webris.org/)

#### Website Goals and page descriptions

   - [Data Runs Deep - AABC](https://datastudio.google.com/reporting/1lK4qQV1orRoyd1s_mYeNt-Mbye4f40YT/) by [Data Runs Deep](http://www.datarunsdeep.com.au/)

#### Page Load

   - [eCommerce speed](https://datastudio.google.com/u/0/reporting/0B-7yurpNRXouUzNibGNsYlBzT2s/) by Canonicalized
   - [Demo - Technical performance indicators for your website](https://datastudio.google.com/reporting/0B1Pzjx-lZIhbYkNia3VqV3V2WDA/) by [Owox](https://www.owox.com/)

#### Engagement

   - [Datasaurus-Rex Google Analytics & YouTube Dashboard](https://datastudio.google.com/u/0/reporting/0ByVApA41aYJibW1feEkyWjNFN3c/) by [Datasaurus Rex](https://datasaurus-rex.com/)

#### Acquisition

   - [GA Acquisition Overview with Data Control](https://datastudio.google.com/u/0/reporting/0B_U5RNpwhcE6T19aRHE1QWRqN3M/) by Unknown

#### Behaviour

   - [GA Behavior Overview with Data Control](https://datastudio.google.com/u/0/reporting/0B_U5RNpwhcE6dDFzTHNtMC1UZnc/) by [Waar Gaan We Eten](https://waargaanweeten.home.blog/)

#### Ecommerce

   - [https://datastudio.google.com/u/0/reporting/0B2-rNcnRS4x5UG50LTBMT0E4aXM/page/nQN](https://datastudio.google.com/u/0/reporting/0B2-rNcnRS4x5UG50LTBMT0E4aXM/) by 
   - [https://datastudio.google.com/u/0/reporting/1rHTK9qrgLX695_W0fGTqPU-djw13O0Mm/page/zNjM](https://datastudio.google.com/u/0/reporting/1rHTK9qrgLX695_W0fGTqPU-djw13O0Mm/)
   - [https://datastudio.google.com/reporting/0BzHxHRjCBXe8WVRMa0tULUJGMm8/page/SZaD](https://datastudio.google.com/reporting/0BzHxHRjCBXe8WVRMa0tULUJGMm8/)

#### Technology

   - [https://datastudio.google.com/u/0/reporting/1k35R2Y1kSlcuZcsx08FqiRlaI7aLZGKr/page/zAqM](https://datastudio.google.com/u/0/reporting/1k35R2Y1kSlcuZcsx08FqiRlaI7aLZGKr/)

#### Content

   - [https://datastudio.google.com/u/0/reporting/0B2NrKDhNqfULS3hGc0tFQTVKZzQ/page/1M](https://datastudio.google.com/u/0/reporting/0B2NrKDhNqfULS3hGc0tFQTVKZzQ/)

#### Funnel

   - [https://datastudio.google.com/u/0/reporting/1igHMbckc4tScPBcIX7pmzb1sGAeZHwZz/page/8yDZ](https://datastudio.google.com/u/0/reporting/1igHMbckc4tScPBcIX7pmzb1sGAeZHwZz/)

#### Audience

   - [https://datastudio.google.com/reporting/0B53LFtWUM76uT2RSVmZrMmE2bUk/page/7JPB](https://datastudio.google.com/reporting/0B53LFtWUM76uT2RSVmZrMmE2bUk/)
   - [https://medium.com/centerforcooperativemedia/introducing-the-audience-explorer-dashboard-for-small-publishers-9fbff748c47](https://medium.com/centerforcooperativemedia/introducing-the-audience-explorer-dashboard-for-small-publishers-9fbff748c47)

#### A/B Tests

   - [https://stories.scandiweb.com/live-mode-dashboard-for-a-b-test-results-with-data-studio-e3b476f181a8](https://stories.scandiweb.com/live-mode-dashboard-for-a-b-test-results-with-data-studio-e3b476f181a8)

### Google Search Console Reports

   - [http://online-behavior.com/analytics/search-console-data-studio](http://online-behavior.com/analytics/search-console-data-studio)
   - [https://www.aleydasolis.com/en/search-engine-optimization/using-google-data-studio-actionable-search-console-performance-report/](https://www.aleydasolis.com/en/search-engine-optimization/using-google-data-studio-actionable-search-console-performance-report/)
   - [https://helpfullee.com/google-search-console-data-studio-1/](https://helpfullee.com/google-search-console-data-studio-1/)
   - [https://medium.com/@singularbean/google-search-console-data-into-google-bigquery-3e794127fa08](https://medium.com/@singularbean/google-search-console-data-into-google-bigquery-3e794127fa08)

### Google Ads Reports

   - [https://datastudio.google.com/u/0/reporting/0B_U5RNpwhcE6ckdmZEJ0ZDJXUnM/page/VgD](https://datastudio.google.com/u/0/reporting/0B_U5RNpwhcE6ckdmZEJ0ZDJXUnM/)
   - [https://datastudio.google.com/u/0/reporting/1IdigljFLqsYdRgIv2se_r4c4fXL45-18/page/hpbQ](https://datastudio.google.com/u/0/reporting/1IdigljFLqsYdRgIv2se_r4c4fXL45-18/)
   - [https://oneppcagency.co.uk/everything-else/data-studio-adwords-template/](https://oneppcagency.co.uk/everything-else/data-studio-adwords-template/)
   - [https://datastudio.google.com/reporting/0BzxVL_5BUjZhWm93VHJFZHl3NGs/page/B2GB](https://datastudio.google.com/reporting/0BzxVL_5BUjZhWm93VHJFZHl3NGs/)

### Social Media Reports

   - [https://datastudio.google.com/u/0/reporting/0BxGPgjQHCLwZWVAyNDJMLVNYWFU/page/mA7C](https://datastudio.google.com/u/0/reporting/0BxGPgjQHCLwZWVAyNDJMLVNYWFU/)
   - [https://datastudio.google.com/u/0/reporting/1hSOTY3Ea_fMmdylPu5ZVxow4-YkvCDYK/page/KgJb](https://datastudio.google.com/u/0/reporting/1hSOTY3Ea_fMmdylPu5ZVxow4-YkvCDYK/)
   - [https://datastudio.google.com/reporting/0B1Pzjx-lZIhbS2FjM19Hdl8xLXc/page/dXmD](https://datastudio.google.com/reporting/0B1Pzjx-lZIhbS2FjM19Hdl8xLXc/)
   - [https://www.rivaliq.com/blog/ultimate-social-media-analytics-dashboard/](https://www.rivaliq.com/blog/ultimate-social-media-analytics-dashboard/)
   - [https://www.lovesdata.com/blog/social-dashboard-google-data-studio](https://www.lovesdata.com/blog/social-dashboard-google-data-studio)

### Cloudflare Report

   - [Final - Cloudflare Logs Analysis for mydomain.com](https://datastudio.google.com/u/0/reporting/1ez3m7Yf8AZLfM6aYRjfgF0pPpRvOwhTh/) by [Cloudflare](https://www.cloudflare.com/)

### Errors Report

   - [Demo - Technical performance indicators for your website](https://datastudio.google.com/reporting/0B1Pzjx-lZIhbYkNia3VqV3V2WDA/) by [Owox](https://www.owox.com/)

### Glossary Page

   - [The Ultimate Google Analytics Glossary – 2019 Edition](https://www.lovesdata.com/blog/google-analytics-glossary) by [Loves Data](https://www.lovesdata.com)

### A Guide to Designing a Report

   - [Perfect Your Google Data Studio Dashboards with 7 Laws of UX](https://supermetrics.com/blog/laws-ux-data-studio) by [Supermetrics](https://supermetrics.com/)

### A Collections of Google Data Studio Report Templates

   - [Google Data Studio Report Gallery](https://datastudiogallery.appspot.com/gallery) by Google
   - [Google Data Studio Resources](https://datastudio.google.com/u/0/reporting/0B2lgFyX5qOqhbFE5RllsdFdtMXc/) by [Helpfullee](https://helpfullee.com/)
   - [Google Data Studio templates](https://supermetrics.com/template-gallery/google-data-studio) by [Supermetrics](https://supermetrics.com/)
   - [Google Data Studio Tumblr page](https://datastudio.tumblr.com/) by DataStudio

## Google Data Studio Feature Requests

It's a list of features that would make creating and managing reports in Google Data Studio much easier.

- Relative links to pages in the report so that when you copy a report links don't point to the original report.
- Editing header text in tables, metrics name and comparison label in scorecards to make them more descriptive or shorter.
- Adding multiple comparison dates in scorecards, tables, charts, etc., e.g. MoM and YoY.
- Setting theme variable colours, which can be used as default colour by all tables, charts and graphs. The ideal solution would allow users to adjust the colours used by all tables, charts and graphs on all pages with a few clicks.
- A way to show sessions by major browser versions, using dimensions or calculated fields, e.g. Chrome 72.0 instead of 72.0.3626.109, 72.0.3626.96, 72.0.3626.119, etc. Also there seems to be always zero after the first full stop. I wonder, why is that?
- Taking the domain name from Google Analytics so that it can be used in calculated fields with hyperlinks and it does not need to be manually specified when the report is used for to analyse the traffic of a new website.
- Having positive and negative change colours switched by default for the bounce rate and all page load. E.g. an increase in bounce rate showing by default in red, while a decrease in green.
- Ability to set positive and negative change colours for each column with a '% Change' metric. E.g. the positive change colour for Sessions is green, while the positive change colour for bounce Rate should be red.
- Renaming positive and negative change colours titles to increased and decreased change colours, as it's not always accurate. E.g. Increase in bounce rate or page load is not something positive for a website.
- Official Google My Business connector for Google Data Studio by Google.