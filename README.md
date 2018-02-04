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
    - PRPL
    - App Shell
    - App Manifest
        - Installable
    - Service Worker
        - Offline
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
    - Web app performance statistics
        - http://beta.httparchive.org/reports/page-weight#bytesJs
        - 40% of JavaScript downloaded is unused.
        - 90% of sites are sending ~1mb gzipped js (~ 4mb, 4s on parse and compile)
        - 35s time to interactive
    - Mobile growth in Africa
    - Connectivity in South Africa
        - http://www.internetlivestats.com/internet-users-by-country/
        - https://www.gsma.com/mobileeconomy/sub-saharan-africa-2017/
    
    - Twitter lite?
    - HNPWA?



https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/
https://developers.google.com/web/fundamentals/performance/prpl-pattern/
https://developers.google.com/web/fundamentals/architecture/app-shell
https://developers.google.com/web/fundamentals/web-app-manifest/
https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/javascript-startup-optimization/
https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/
https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/offline-for-pwa
https://developers.google.com/web/fundamentals/primers/service-workers/
https://developers.google.com/web/fundamentals/

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