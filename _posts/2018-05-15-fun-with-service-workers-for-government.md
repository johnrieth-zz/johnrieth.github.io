---
layout: post
title: Fun with Service Workers for Government
categories: design service-workers
---
Service workers give developers to provide fast and offline experiences for users. [Progressive web apps](https://developer.mozilla.org/en-US/Apps/Progressive) use service workers and other web APIs to make web apps have a similar experience as native apps. I have created two examples using service workers with the [U.S. Web Design System landing page template](https://designsystem.digital.gov/page-templates/landing/). I used the template because I find it easy to work with and wanted to see how a government site might take advantage of service workers. 

1. Example one uses [workbox](https://developers.google.com/web/tools/workbox/), a tool from Google that adds offline support for websites. The example site using workbox is available at <https://johnrieth.github.io/uswds-sw/>. The service worker registers but the site doesn't load offline. 
2. Example two uses vanilla JavaScript for the service worker. The site is installable using Chrome and Firefox on Android. I have had success installing on Windows 10 but I have not been able to install the last two times I tried. You can experience the installable site at <https://johnrieth.github.io/uswds-pwa-install/>. The service worker currently tries and fails to cache too many assets. 

I think service workers and progressive web apps could be useful for government websites to provide uniform user experiences to people no matter their internet speeds.
