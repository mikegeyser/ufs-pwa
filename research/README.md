# Progressive Web Apps - What are they and why should you care?

The hype is real. 

When the excitement about a technology reaches fever-pitch, it becomes difficult to separate the signal from the noise. In the case of Progressive Web Apps (PWAs), it's become very difficult to pin down exactly what they are. Are they indeed the 'next big thing'™ or are they just another fashion trend. Will life carry on if you let the PWA train pass you by, or should you be paying attention?

This talk will explain what PWAs are, and what they are not. It will detail the design patterns, technologies and philosophies that they are composed of. Finally, it will look at real world usage trends, for both web and mobile, and attempt to answer the burning question: should you care about PWAs?

# Bio

Mike Geyser is a Google Developer Expert in Web Technologies, working in the R&D team at BBD. He is a co-organiser of the Jozi.JS and Docker Johannesburg meetup groups, and is a frequent technical speaker. He has been hacking on the web since GeoCities was a 'thing', and has the keening wail of dialup modem etched into his subconscious. While he is fluent in several ‘golden hammer’ programming languages, he has a long-lived love affair with JavaScript, and cannot see its (many, obvious) flaws. He has worked on lots of interesting enterprise applications, but it is the challenges of the public web that really appeal to him - having spent his formative years building transactional websites. He is always eager to talk about the web platform, but be warned, he is prone to hyperbole.

# Structure

- Introduction
    - Need a fresher one, that adds the GDE thing.
    - Agenda
- What are PWAs
    - Definition
        - Coined in 2015 - Frances Berriman and Alex Russell
        -  "apps taking advantage of new features supported by modern browsers [...] that let users upgrade web apps to progressive web applications in their native operating system"
        https://developers.google.com/web/progressive-web-apps/

            - Reliable 
                - Load instantly and never show the downasaur, even in uncertain network conditions.
            - Fast 
                - Respond quickly to user interactions with silky smooth animations and no janky scrolling.
            - Engaging 
                - Feel like a natural app on the device, with an immersive user experience.
                
        - Characteristics:
            - https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/
        
            - Progressive 
                - Work for every user, regardless of browser choice because they’re built with progressive enhancement as a core tenet.
            - Responsive 
                - Fit any form factor: desktop, mobile, tablet, or forms yet to emerge.
            - Connectivity independent 
                - Service workers allow work offline, or on low quality networks.
            - App-like 
                - Feel like an app to the user with app-style interactions and navigation.
            - Fresh 
                - Always up-to-date thanks to the service worker update process.
            - Safe 
                - Served via HTTPS to prevent snooping and ensure content hasn’t been tampered with.
            - Discoverable 
                - Are identifiable as “applications” thanks to W3C manifests[6] and service worker registration scope allowing search engines to find them.
            - Re-engageable 
                - Make re-engagement easy through features like push notifications.
            - Installable 
                - Allow users to “keep” apps they find most useful on their home screen without the hassle of an app store.
            - Linkable 
                - Easily shared via a URL and do not require complex installation.
    
    - App Shell
        - https://developers.google.com/web/fundamentals/architecture/app-shell
        - The app "shell" is the minimal HTML, CSS and JavaScript required to power the user interface and when cached offline can ensure instant, reliably good performance to users on repeat visits

    - Service Worker
        - 
        - Offline
        - https://developers.google.com/web/fundamentals/primers/service-workers/
        - https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/javascript-startup-optimization/
        - https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/
        - https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/offline-for-pwa

    - App Manifest
        - https://developers.google.com/web/fundamentals/web-app-manifest/
        - Installable
            - https://developers.google.com/web/fundamentals/app-install-banners/
    
    - PRPL
        - https://developers.google.com/web/fundamentals/performance/prpl-pattern/
        - PRPL is a pattern for structuring and serving Progressive Web Apps (PWAs), with an emphasis on the performance of app delivery and launch.
            - Push critical resources for the initial URL route.
            - Render initial route.
            - Pre-cache remaining routes
            - Lazy-load and create remaining routes on demand.

    - UX

    - Performance
        - Download size
        - "Loading is a journey"
        - Time to interactive
        - Time to meaningful paint
        - Parse cost
        - Performance budget
             - First load: 5s
             - ~160-170kb
        
    - Lighthouse

- Why should we care about PWAs
    - Mobile App Usage statistics
        - ± 5 Billion Devices Connected to the Web
        - More mobile than desktop
        - 13% of time on mobile is on web, 87% on native apps.
        - 80% of time is spent in 3 apps.
        - The average user installs zero new apps per month.
        - https://techcrunch.com/2017/05/04/report-smartphone-owners-are-using-9-apps-per-day-30-per-month/
        - https://www.comscore.com/Insights/Presentations-and-Whitepapers/2017/The-2017-US-Mobile-App-Report
        - http://www.businessofapps.com/data/app-statistics/
        - https://sweetpricing.com/blog/2017/02/average-app-file-size/
    
    - Web app performance statistics
        - http://beta.httparchive.org/reports/page-weight#bytesJs
        - 40% of JavaScript downloaded is unused.
        - 90% of sites are sending ~1mb gzipped js (~ 4mb, 4s on parse and compile)
        - 35s time to interactive
        - After 3s, 20% of users abandon the session        
        
    - Mobile growth in Africa
        -- http://www.internetworldstats.com/stats.htm
    - Connectivity in South Africa
        - http://www.internetlivestats.com/internet-users-by-country/
        - https://www.gsma.com/mobileeconomy/sub-saharan-africa-2017/
    
    - Twitter lite?
    - Google maps
        - https://www.google.com/maps/@-26.1865602,28.0177577,15z?force=pwa
    - HNPWA?
    - https://twitter.com/davatron5000/status/959140161400590341


- Are they ready yet?
    - Chrome
        - https://twitter.com/davatron5000/status/959140161400590341
    - Firefox
        - https://hacks.mozilla.org/2018/01/firefox-58-the-quantum-era-continues/
    - Edge
        - https://blogs.windows.com/msedgedev/2018/02/06/welcoming-progressive-web-apps-edge-windows-10/
    - Safari
        - https://webkit.org/blog/8090/workers-at-your-service/
    
    - https://jakearchibald.github.io/isserviceworkerready/




https://developers.google.com/web/fundamentals/

https://www.smashingmagazine.com/2016/08/a-beginners-guide-to-progressive-web-apps/
https://www.smashingmagazine.com/2016/09/the-building-blocks-of-progressive-web-apps/

The Web for the Entire World (Chrome Dev Summit 2017) https://www.youtube.com/watch?v=eG0ILA2k5qo&t=2s

Fast By Default: Modern Loading Best Practices (Chrome Dev Summit 2017) https://www.youtube.com/watch?v=_srJ7eHS3IM&t=2s
Kickstarting Your Journey to Progressive Web Apps (Chrome Dev Summit 2017) https://www.youtube.com/watch?v=goafiwzhKMI&t=3s
Progressive Web Apps: Integrating with Browsers and Operating Systems (Chrome Dev Summit 2017) https://www.youtube.com/watch?v=_sLa0qhuqcA&t=3s
From Website to Progressive Web App (GDD Europe '17) https://www.youtube.com/watch?v=KRSTpo6gqqU&t=133s
Instant Loading: Building offline-first Progressive Web Apps - Google I/O 2016 https://www.youtube.com/watch?v=cmGr0RszHc8
Addy Osmani: The Browser Hackers Guide To Instantly Loading Everything | JSConf EU 2017 https://www.youtube.com/watch?v=7vUs5yOuv-o&t=84s
Production Progressive Web Apps With JavaScript Frameworks (Google I/O '17) https://www.youtube.com/watch?v=aCMbSyngXB4&t=113s

https://jakearchibald.github.io/isserviceworkerready/

https://infrequently.org/2017/10/can-you-afford-it-real-world-web-performance-budgets/

Progressive Web Apps: What, Why, and How? https://www.youtube.com/watch?v=eodArdGRIVQ

