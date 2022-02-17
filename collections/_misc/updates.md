---
layout: default
title: Updates
description: Breeze updates
order: 50
---

# Updates

## 0.12.0

> Feb 17, 2022

**Module Updates**

 -  🚀 Added critical images preloading. This feature decreases time of
    Largest Contentful Paint. _No additional actions are required to activate this feature_.
 -  🚀 Added "Use CSS critical path" config option support. Activate it at
    _Stores > Configuration > Advanced > Developer > CSS Settings > Use CSS critical path_.
 -  🚀 Added js chunking mechanism that improves page load time on slow internet
    connections. _No additional actions are required to activate this feature_.
 -  🔧 Slightly improve js and html minification.

**Theme Updates**

 -  💄 Improved chevron position in collapsible layered navigation filters.
 -  💄 Added ability to wrap product thumbnails to the new line instead of overflowed scrolling.
 -  🔧 Fixed video centering at product page gallery.

## 0.11.0

> Feb 8, 2022

 -  **Added minimalistic email styles.** We've took Magento/blank email structure
    as a base, so you will find it super easy to integrate with existing blank/luma
    customizations. See the tutorial on [how to add email customizations from child theme](/email-styles).
 -  Improve bundle product details at order view page.
 -  Fixed missing options at product page for Bundle Products.
 -  Fixed error at homepage about unknown "new" attribute on fresh Magento installations.

## 0.10.0

> Jan 28, 2022

**Theme Updates**

 -  **All Swissup modules are now compatible with Breeze!**
 -  Fixed grouped product view on mobile devices.
 -  Move navigation container below header to allow to use sticky menu.
 -  Better compatibility with third-party modules.

**Module Updates**

 -  Support for jQuery-like api in ajax requests: `$.ajax`, `$.post`, `$.get`.
 -  Added support for multiple expanded tabs. This is useful when transforming tabs into accordion.
 -  Improved click handling inside modal popups.
 -  Improved SPA experience.

## 0.9.1

> Jan 14, 2021

 -  Allow to create nested view components.
 -  Fixed js error when recaptcha is enabled in product review form.
 -  Fixed "getTemplate" error when third-party component is not available in Breeze.
 -  Fixed responsive images sizes on the homepage.
