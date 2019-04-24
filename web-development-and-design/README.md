# Web Development

## Browsers

[Blockstack](https://blockstack.org/) - “Blockstack is a new internet for decentralized apps where users own their data. A browser is all that’s needed to get started.”

[Brave](https://brave.com/) \#software - “Browse faster by blocking ads and trackers that violate your privacy and cost you time and money.”

[BrowserStack](https://www.browserstack.com/) - "App & Browser Testing Made Easy. Give your users a seamless experience by testing on 2000+ real devices and browsers. Don't compromise with emulators and simulators."

[BrowserStack: Free Testing on Microsoft Edge](https://www.browserstack.com/test-on-microsoft-edge-browser#) - "Until now, developers have been relying on virtual machines or PC’s with Windows 10 to test their products and websites on Microsoft Edge. To provide an easier way to test, Microsoft and BrowserStack are partnering to give developers a cloud-based infrastructure to instantly test and ship great experiences on Microsoft Edge."

[Microsoft Edge virtual machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) - "Test Microsoft Edge \(EdgeHTML\) and versions of IE8 through IE11 using free virtual machines you download and manage locally."

[WebKit](https://webkit.org/) \#software - “WebKit is the web browser engine used by Safari, Mail, App Store, and many other apps on macOS, iOS, and Linux.”

## Checklists

[The Front-End Checklist](https://frontendchecklist.io/) \#webapp - “🗂 The Front-End Checklist Application is perfect for modern websites and meticulous developers!”

## Development Environments

[Codepen](https://codepen.io/#) \#webapp - “👋 CodePen is a social development environment. At it's heart, it allows you to write code in the browser, and see the results of it as you build. A useful and liberating tool for developers of any skill, and particularly empowering for people learning to code. We focus primarily on front-end languages like HTML, CSS, JavaScript, and preprocessing syntaxes that turn into those things.”

## Email

[Benchmark](https://www.benchmarkemail.com) - “Powerful and Simple Email Marketing. Simple enough for your intern. Design to impress the creative team. Bigger sales to thrill the boss.” \#email

## Frameworks

[Bootstrap](https://getbootstrap.com/) - “Build responsive, mobile-first projects on the web with the world’s most popular front-end component library. Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.”

## HTML

[Twig Documentation](https://twig.symfony.com/doc/2.x/)

## Performance

[Avoiding The Pitfalls Of Automatically Inlined Code](https://www.smashingmagazine.com/2018/11/pitfalls-automatically-inlined-code/) \#article - “Overusing inline CSS or JS code, as opposed to serving code through static resources, can harm the site’s performance. In this article, we will learn how to load dynamic code through static files instead, avoiding the drawbacks of too much inline code.” \#performance \#caching \#wordpress

[Controlling Font Performance with font-display](https://developers.google.com/web/updates/2016/02/font-display?utm_source=lighthouse&utm_medium=extension) \#article - "Deciding the behavior for a web font as it is loading can be an important performance tuning technique. The new font-display descriptor for `@font-face` lets developers decide how their web fonts will render \(or fallback\), depending on how long it takes for them to load."

[Google Fonts and font-display](https://css-tricks.com/google-fonts-and-font-display/) \#article - "The [`font-display`](https://css-tricks.com/almanac/properties/f/font-display/) descriptor in [`@font-face`](https://css-tricks.com/snippets/css/using-font-face/) blocks is really great. It goes a long way, all by itself, for improving the perceived performance of web font loading. Loading web fonts is tricky stuff and having a tool like this that works as well as it does is a big deal for the web. It's such a big deal that Google's own [Pagespeed Insights / Lighthouse](https://developers.google.com/speed/pagespeed/insights/) will ding you for not using it. A cruel irony, as their own Google Fonts \(easily the most-used repository of custom fonts on the web\) don't offer any way to use `font-display`."

[How to Load Web Fonts in 2019 🎆](https://www.youtube.com/watch?v=s-G1m23Emlk)\#video - "After a lot of experimentation I've come across my preferred way of loading web fonts. I have balanced ease of use, i.e. how to implement, with performance."

[Links to cross-origin destinations are unsafe](https://developers.google.com/web/tools/lighthouse/audits/noopener?utm_source=lighthouse&utm_medium=extension) \#article - "When you open another page using `target="_blank"`, the other page may run on the same process as your page, unless [Site Isolation](https://developers.google.com/web/updates/2018/07/site-isolation) is enabled. If the other page is running a lot of JavaScript, your page's performance may also suffer. See [The Performance Benefits of `rel=noopener`](https://jakearchibald.com/2016/performance-benefits-of-rel-noopener/)."

## Security

[Links to cross-origin destinations are unsafe](https://developers.google.com/web/tools/lighthouse/audits/noopener?utm_source=lighthouse&utm_medium=extension) \#article - "The other page can access your `window` object with the `window.opener` property. This exposes an [attack surface](https://en.wikipedia.org/wiki/Attack_surface) because the other page can potentially redirect your page to a malicious URL. See [About rel=noopener](https://mathiasbynens.github.io/rel-noopener/)."

## Typography

[Controlling Font Performance with font-display](https://developers.google.com/web/updates/2016/02/font-display?utm_source=lighthouse&utm_medium=extension) \#article - "Deciding the behavior for a web font as it is loading can be an important performance tuning technique. The new font-display descriptor for `@font-face` lets developers decide how their web fonts will render \(or fallback\), depending on how long it takes for them to load."

[Google Fonts and font-display](https://css-tricks.com/google-fonts-and-font-display/) \#article - "The [`font-display`](https://css-tricks.com/almanac/properties/f/font-display/) descriptor in [`@font-face`](https://css-tricks.com/snippets/css/using-font-face/) blocks is really great. It goes a long way, all by itself, for improving the perceived performance of web font loading. Loading web fonts is tricky stuff and having a tool like this that works as well as it does is a big deal for the web. It's such a big deal that Google's own [Pagespeed Insights / Lighthouse](https://developers.google.com/speed/pagespeed/insights/) will ding you for not using it. A cruel irony, as their own Google Fonts \(easily the most-used repository of custom fonts on the web\) don't offer any way to use `font-display`."

[How to Load Web Fonts in 2019 🎆](https://www.youtube.com/watch?v=s-G1m23Emlk)\#video - "After a lot of experimentation I've come across my preferred way of loading web fonts. I have balanced ease of use, i.e. how to implement, with performance."

[Pixels vs. Ems: Users DO Change Font Size](https://medium.com/@vamptvo/pixels-vs-ems-users-do-change-font-size-5cfb20831773) \#article - “The question was “How many users browse the main Internet Archive site with a default font size other than the common value of 16 pixels?” By knowing this, we would determine how many users would be affected by sizing with relative units like rems/ems. Using the methodology I describe below, we found that the answer is 3.08% of our users. That’s a pretty big number, higher than most counts of the market share of browsers like Internet Explorer, Edge, or Opera Mini.”

## Testing

[BrowserStack](https://www.browserstack.com/) - "App & Browser Testing Made Easy. Give your users a seamless experience by testing on 2000+ real devices and browsers. Don't compromise with emulators and simulators."

[BrowserStack: Free Testing on Microsoft Edge](https://www.browserstack.com/test-on-microsoft-edge-browser#) - "Until now, developers have been relying on virtual machines or PC’s with Windows 10 to test their products and websites on Microsoft Edge. To provide an easier way to test, Microsoft and BrowserStack are partnering to give developers a cloud-based infrastructure to instantly test and ship great experiences on Microsoft Edge."

[Lighthouse Chrome extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk) - "Lighthouse is an open-source, automated tool for improving the performance, quality, and correctness of your web apps. When auditing a page, Lighthouse runs a barrage of tests against the page, and then generates a report on how well the page did. From here you can use the failing tests as indicators on what you can do to improve your app."

[Microsoft Edge virtual machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) - "Test Microsoft Edge \(EdgeHTML\) and versions of IE8 through IE11 using free virtual machines you download and manage locally."

