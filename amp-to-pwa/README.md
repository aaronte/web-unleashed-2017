<h1 align="center">From AMP to PWA: A Modern Web User Journey</h1>

Speaker: [Alberto Medina](https://twitter.com/ialbmedina)

**Ultimate Goal:** An awesome mWeb experience

Common Problems:
* Slow loading
* Unresponsive pages
* Content displaced by ads

State of Affairs
* 75% of mobile sites take 10+ seconds to load
* 53% of mobile site visitors leave after 3 seconds of load time
* 2X more mobile ad revenue for sites that load in 5 seconds vs 19 seconds

What is behind an awesome app UX?
* Secure
* Reliably Fast
* Engaging
* Integrated
* --> Native-like "User Experience"

Progressive Web Apps (PWA)
* Engaging
    * Push notifications
    * Add to Home Screen
* Speed, Reliability
    * Fsst loading
    * Offline access
    * Responsive UI

Accelerated Mobile Pages (AMP)
* AMP Components
    * AMP HTMl
    * AMP JS
    * AMP Cache
* AMP Optimization
    * Asynchonous Loading
    * No Custom JS Allowed
    * Static Layout System
    * Prioritized Content Loading
* AMP Components
    * A CDN for AMP Pages
    * It is optional
    * Provides Validation
    * Uses HTTP/2.0
    * Pre-rendering => "Intant"  Feeling
    * Many Other Optimizations

AMP or PWA?
* AMP to Progressive Web App
    * `<amp-install-serviceworker>`
    * Flow:
        * User discovers content
        * Service Worker installs in the background
        * User is instantly ugpraded to PWA
        * Rakuten Recipe is an example for recipe site
* AMP as Progressive Web App
    * ambbyexample.com
    * `mynet`
        * +25% higher revenue per article
        * 4x faster page load
        * +43% time spent on site
        * +34% more page views
        * -24% lower bounce rates
    
* AMP in Progressive Web App
    * AMP pages aren't just web pages, they're **ultra-portable**, **embeddable**, **content units**
    * Cached shells load instantly on repeated visits
    * Dynamic content then populates the view
    * AMP HTML 
        * AMP Experience
        * PWA Experience
    * Could be achieved w/ `<iframe>`
        * 1 Window
        * 1 AMP Library Instances
        * 1 Document
    * `Shadow DOM` to the rescue!
        * 1 Window
        * 1 AMP Library Instance
        * Infinite Documents
    * In Practice:
        * https://github.com/ampproject/amp-publisher-sample/tree/master/amp-pwa
        * The Shadown Reader App
            * https://github.com/ampproject/amp-publisher-sample/tree/master/amp-pwa-reader
            * Server-less SPA
            * App Shell Architecture (2 Skeleton UI)
            * Uses **The Guardian** content API
            * Full URL-based navigation
            * 60 FPS animation
            * etc.
        * https://github.com/GoogleChrome/workbox
   
   PWAMP FTW!
   * Always fast, no matter what
   * Greate distribution built-in
   * Progressively enhanced
   * One backend to rule them all
   * Less client complexity, fewer deply targets
