# APIs

- [Data platform+dashboard for making browsers more API compatible](https://wpt.fyi/results/?label=experimental&label=master&aligned)
- [A site to test the interaction of web APIs and browser permissions.](https://github.com/chromium/permission.site)
- https://web.dev/new-patterns-for-amazing-apps
- https://blog.stackblitz.com/posts/introducing-webcontainers
- https://github.com/NOtherDev/whatwebcando
- https://github.com/samdutton/simpl
- [How to Get Around Newspaper Paywalls in 2019](https://t.co/pVtMutYzns)
- [Trying out and demonstrating different browser APIs](https://github.com/vkallore/browser-apis)
- https://github.com/deebloo/things-you-can-do-in-a-web-worker
- [This repo contains a non exhaustive list of less-known features implemented in browsers today.](https://github.com/luruke/browser-2020)
- [new MutationObserver()](https://www.seancassidy.me/genius-blocker.html)
- https://github.com/AurelioDeRosa/HTML5-API-demos
- https://blog.greenroots.info/10-lesser-known-web-apis-you-may-want-to-use-ckejv75cr012y70s158n85yhn
- https://formidable.com/blog/2020/resize-observer
- https://webkit.org/blog/11312/meet-face-id-and-touch-id-for-the-web + https://twitter.com/webkit/status/1318256785447211009
- https://blog.redteam.pl/2020/08/stealing-local-files-using-safari-web.html
- https://iandunn.name/2019/11/29/minimal-cachestorage-cache-api-example
- https://stackoverflow.com/questions/16808486/explanation-of-window-performance-javascript
- https://www.smashingmagazine.com/2021/01/web-expose-hardware-capabilities
- https://engineering.q42.nl/passwordless-authentication
- [Proposal for an API which would allow grabbing a screenshot.](https://github.com/eladalon1983/mediacapture-screenshot)
- https://www.vector-logic.com/blog/posts/on-request-animation-frame-and-embedded-iframes
- https://github.com/azu/url-cheatsheet
- https://www.macarthur.me/posts/navigating-the-event-loop
- https://richiemccoll.com/javascript-scheduling
- https://austingil.com/user-location-is-a-lie
- [Flexible web API for encoding and decoding audio and video](https://github.com/w3c/webcodecs)

# Bookmarklet

- Open in Gmail

```javascript
javascript: (() =>
  (window.location.href = `https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=yourGmailAddress@gmail.com&su=${document.title}&body=${window.location.href}`))();
```

- [Speed controls](https://codepen.io/wilman/pen/ZWdEPX)
- https://github.com/Blumed/make-bookmarklets
- https://github.com/marcobiedermann/awesome-bookmarklets
- [Find out which element is scrolling.](https://gist.github.com/brumm/74fd7eaafd50c8477519)
- [Performance-Bookmarklet helps to analyze the current page through the Resource Timing API, Navigation Timing API and User-Timing - requests by type, domain, load times, marks and more. Sort of a light live WebPageTest.](https://github.com/micmro/performance-bookmarklet)
- https://www.secjuice.com/make-your-own-custom-osint-bookmarklet-tools-part-ii
- https://emanuelduss.ch/2020/06/humble-book-bundle-download-bookmarklet
- [world smallest office suite](https://zserge.com/posts/awfice)
- [Bookmarklets for sending emails and adding todo items](https://sashko.dev/bookmarklets)
- https://www.farai.xyz/notes/tech-tips/please-archive-content
- https://github.com/ThomasOrlita/awesome-bookmarklets
- [Script Kit. Automate Anything](https://github.com/johnlindquist/kit)
- https://ryangjchandler.co.uk/posts/bookmarklets-you-should-definitely-be-using
- [Read premium articles for free](https://github.com/sugoidesune/readium)
- https://knowler.dev/blog/open-in-codesandbox-bookmarklet
- https://github.com/t-mart/kill-sticky
- [Linter for Responsive Images](https://github.com/ausi/RespImageLint)
- https://jojo.io/posts/bookmarklets-speed
- [Get your Kindle highlights out of the cloud and onto your computer](https://github.com/TristanH/bookcision) + https://alan.norbauer.com/articles/bookcision
- https://github.com/jakecreps/osint-bookmarklets
- https://eriksolsen.com/blog/dynamic-bookmarks-in-google-chrome
- https://gabrielsroka.github.io/webpages/bookmarklets.htm
- https://github.com/satisfice/web-testing-bookmarklets

# `Clipboard API`

- https://alexharri.com/blog/clipboard
- https://wolfgangrittner.dev/how-to-use-clipboard-api-in-firefox

# Document Object Model (DOM)

- [Common tasks of managing HTML DOM with vanilla JavaScript](https://htmldom.dev)
- https://github.com/mikewest/deprecating-document-domain
- https://danlevy.net/you-may-not-need-axios
- [Everything you (n)ever wanted to know about touch and pointer events](https://github.com/patrickhlauke/getting-touchy-presentation)
- https://labs.detectify.com/2016/12/08/the-pitfalls-of-postmessage
- https://chrisrng.svbtle.com/using-url-createobjecturl
- [POST data to the server even inside onbeforeunload, etc where XHR/fetch isn't reliable.](https://twitter.com/_jayphelps/status/1244794448237735936)
- [Async DOM listeners](https://twitter.com/WebReflection/status/1260474785894666242)
- [.dom is a tiny (512 byte) template engine that uses virtual DOM and some of react principles.](https://github.com/wavesoft/dot-dom)
- https://www.malgol.com/how-to-reload-an-iframe-in-javascript
- [Avoid appending to innerHTML](https://twitter.com/jaffathecake/status/1322136845199810560)
- https://github.com/Schepp/async-document.write
- https://hachibu.net/posts/2020/keyboard-events-tldr
- [bypass document.write](https://twitter.com/LiveOverflow/status/1319325896545865728)
- https://css-tricks.com/using-abortcontroller-as-an-alternative-for-removing-event-listeners
- https://benfrain.com/building-a-table-of-contents-with-active-indicator-using-javascript-intersection-observers
- [What is document.domain?](https://twitter.com/zcorpan/status/1202958734949060608)
- [appending multiple elements to the DOM?](https://twitter.com/paul_irish/status/1169841234438848519)
- [Find out which element is scrolling](https://gist.github.com/brumm/74fd7eaafd50c8477519) + https://twitter.com/funkensturm/status/1222616188485799937
- [is there a way to debug dom events in a timeline?](https://twitter.com/sseraphini/status/1377218954851201025)
- [A zero friction custom elements like primitive.](https://github.com/WebReflection/builtin-elements)
- [DOM event data scraped from MDN](https://github.com/eddyerburgh/dom-event-types)
- https://workspaceupdates.googleblog.com/2021/05/Google-Docs-Canvas-Based-Rendering-Update.html + https://news.ycombinator.com/item?id=27129858
- https://whistlr.info/2020/understanding-load
- [DOM Traversing and Scraping using GraphQL](https://github.com/syrusakbary/gdom)
- [Collection of functions used for DOM manipulations](https://github.com/revolter/min)
- [Fire mouse events when a user intends it](https://github.com/tristen/hoverintent)
- https://github.com/0xGodson/blogs/blob/master/_posts/2022-07-21-art-of-dom-clobbering.md
- https://github.com/cms/domready
- https://github.com/mgp/book-notes/blob/master/advanced-dom-scripting.markdown
- https://frontendmasters.com/blog/vanilla-javascript-todomvc
- [A simple method to invoke a function after the browser has rendered & painted a frame](https://github.com/andrewiggins/afterframe)
- https://www.macarthur.me/posts/options-for-removing-event-listeners
- https://www.macarthur.me/posts/when-dom-updates-appear-to-be-asynchronous
- [random overflowing element](https://carbon.now.sh/nZLVj2OK0WPlLILIXn4E)
- https://blog.andri.co/022-should-i-use-ecode-or-ekey-when-handling-keyboard-events
- https://noncombatant.org/2017/11/07/problems-of-urls
- https://macarthur.me/posts/options-for-removing-event-listeners

# new IntersectionObserver()

- [Using the Intersection Observer web API to improve performance.](https://www.growingwiththeweb.com/2018/01/intersection-observer.html)
- [Intersection Observer by Kevin Powell](https://m.youtube.com/playlist?list=PL4-IK0AVhVjOmWeHkUz34FxIFP8I8X1ae)
- https://github.com/snewcomer/intersection-observer-admin
- https://ryanmulligan.dev/blog/sticky-header-scroll-shadow

# new MutationObserver()

- [syntax-fm-sticky-show-notes.user.js](https://gist.github.com/salembeats/8d1b73d2cf14ba012039ac844d0c79c6)

# new URL()

- [? vs #](https://github.com/robinmoisson/staticrypt/issues/156)
- https://www.mandiant.com/resources/blog/url-obfuscation-schema-abuse + https://twitter.com/ankit_anubhav/status/1592109955641126912
- https://github.com/jakelazaroff/til/blob/main/javascript/load-a-user-created-javascript-file-in-the-browser.md

# new Worker()

- [Why don't we just move all JS to a web worker?](https://twitter.com/dan_abramov/status/1234297789938589696) + https://docs.google.com/document/d/1nu0EcVNC3jtmUVWL8Gs5eCj2p_984kamNhG2nS9gOC0/edit#heading=h.e6n21l1n04rc
- [Is ServiceWorker intended to be a SharedWorker that works offline?](https://twitter.com/jlongster/status/1241010515071111168)
- https://github.com/delapuente/service-workers-101
- [Tips for working with ServiceWorker](https://github.com/popeindustries/sw-tips)
- [ServiceWorker Testing made easy ](https://github.com/popeindustries/sw-tester)
- https://dev.to/thepassle/the-mental-gymnastics-of-service-worker-257g
- https://github.com/dominiccooney/Service-Worker-Performance
- https://jychp.medium.com/how-to-bypass-cloudflare-bot-protection-1f2c6c0c36fb + https://twitter.com/XssPayloads/status/1376382674173112320
- https://github.com/offlinefirst/research
- https://souporserious.com/bundling-workers-for-npm
- [Measure cpu cache size client side in Javascript](https://github.com/allanlw/cache_size)
- https://dagster.io/blog/web-workers-performance-issue
- https://github.com/astoilkov/main-thread-scheduling
- [Stuff I wish I'd known sooner about service workers](https://gist.github.com/Rich-Harris/fd6c3c73e6e707e312d7c5d7d0f3b2f9)
- https://philipwalton.com/articles/smaller-html-payloads-with-service-workers
- https://blog.persistent.info/2021/08/worker-loop.html
- [load modules into web workers, access them asynchronously](https://github.com/bitair-org/concurrent.js)
- [monitoring tool to implement client-side caching](https://github.com/oslabs-beta/tulo-js)
- https://thepassle.netlify.app/blog/i-overengineered-my-blog

# Engine

- https://dev.to/lydiahallie/javascript-visualized-the-javascript-engine-4cdf
- https://github.com/a0viedo/demystifying-js-engines
- https://zon8.re/posts/v8-chrome-architecture-reading-list-for-vulnerability-researchers
- https://zon8.re/posts/jsc-architecture-reading-list-for-vulnerability-researchers + https://zon8.re/posts/jsc-internals-part1-tracing-js-source-to-bytecode
- [Notes and resources related to V8 and thus Node.js performance.](https://github.com/thlorenz/v8-perf)
- https://github.com/hex13/javascript-visual-explanations#javascript-engines
- https://deepu.tech/memory-management-in-v8
- https://twitter.com/awesomekling/status/1314552767021813760
- https://github.com/danbev/learning-v8
- https://github.com/danbev/learning-libuv
- https://www.cyberark.com/resources/threat-research-blog/the-mysterious-realm-of-javascriptcore
- [a very small v8 javascript runtime for linux only](https://github.com/just-js/just)
- https://mrale.ph/v8/resources.html
- [V8 sandbox](https://twitter.com/5aelo/status/1529863751868076032)
- https://docs.google.com/presentation/d/1NVyRgitg-2CyN3BuoZZF6F-Dw8PuDybFjkFICAyYPHo
- [Part 1 covers V8 internals such as objects, properties, and memory optimizations](https://jhalon.github.io/chrome-browser-exploitation-1)
- [Building Chrome V8 on Windows](https://gist.github.com/jhalon/5cbaab99dccadbf8e783921358020159)
- [Bun? Deno? Node.js? Creating your own JavaScript Runtime using V8, Libuv and more](https://github.com/ErickWendel/myownnode)
- https://github.com/eatonphil/one-pass-code-generation-in-v8
- https://github.com/wdv4758h/awesome-jit
- https://github.com/mgaudet/SpiderMonkeyBibliography
- https://bun.sh/blog/how-bun-supports-v8-apis-without-using-v8-part-2
- https://medium.com/@stankoja/v8-bug-hunting-part-1-setting-up-the-debug-environment-7ef34dc6f2de
- [V8 has a lot of different string types](https://github.com/v8/v8/blob/941b945b/src/objects/objects.h#L134-L151)
- [Java Bindings for V8](https://github.com/eclipsesource/J2V8)

# Exploit

- [Awesome list of browser exploitation tutorials ](https://github.com/Escapingbug/awesome-browser-exploit)
- [Browser Exploitation - LiveOverflow](https://m.youtube.com/playlist?list=PLhixgUqwRTjwufDsT1ntgOY9yjZgg5H_t)
- [Browser logic vulnerabilities DB](https://github.com/Metnew/uxss-db)
- [Microsoft Edge (Chromium) - EoP via XSS to Potential RCE](https://twitter.com/Qab/status/1209457592126324737)
- [Software-based Side-Channel Attacks and Defenses in Restricted Environments (PhD thesis)](https://misc0110.net/web/files/phd_thesis.pdf)
- https://www.ryanpickren.com/webcam-hacking + https://twitter.com/domenic/status/1245871443729985536
- [Building a 1-day Exploit for Google Chrome](https://twitter.com/theori_io/status/980272605117612033)
- https://github.com/qazbnm456/awesome-cve-poc
- https://github.com/allpaca/chrome-sbx-db
- https://googleprojectzero.blogspot.com/p/0day.html
- https://github.com/SpiralBL0CK/Browser-Pwning-
- https://github.com/StarCrossPortal/bug-hunting-101
- https://github.com/nccgroup/exploit_mitigations
- https://github.com/cezary-sec/awesome-browser-security + https://m.youtube.com/playlist?list=PLuHcjpINS_OJntoGxRu0FEju5ak0yE_46
- [Practical Exploitation of Math.random on V8](https://github.com/d0nutptr/v8_rand_buster)
- https://github.com/m1ghtym0/browser-pwn

# Extension

- [Extension source viewer](https://github.com/Rob--W/crxviewer)
- https://github.com/jxnl/youtube-summary-chrome
- [A new tab page extension with material design and useful features](https://github.com/Alexays/Epiboard)
- https://github.com/OsaSoft/youtube-better-subscriptions
- [Uncovering a crazy privilege escalation from Chrome extensions](https://0x44.xyz/blog/cve-2023-4369/index.html) + https://twitter.com/deryilz/status/1724506569973416282
- https://github.com/msfrisbie/spy-extension + https://mattfrisbie.substack.com/p/spy-chrome-extension
- [Encrypt Gmail with PGP](https://github.com/FlowCrypt/flowcrypt-browser)
- [Check how trackable you are based on your browser extensions](https://github.com/z0ccc/extension-fingerprints)
- https://ninoseki.github.io/2020/05/16/browser-extension.html
- [decide which cookies you want and don’t want, auto-accepts cookie pop-ups for you, and warns you whenever it finds a website not respecting your preferences](https://www.super-agent.com)
- https://github.com/ryanckulp/twitter_ad_blocker
- [The browser extension framework](https://github.com/PlasmoHQ/plasmo)
- [Skip youtube video sponsors](https://github.com/ajayyy/SponsorBlock)
- [Chrome Extension for one click downloading all resources files and keeping folder structures](https://github.com/up209d/ResourcesSaverExt)
- [A Chrome extension that adds a 3d photo effect to instagram pages](https://github.com/cyrildiagne/instagram-3d-photo)
- [Firefox addon for passively detecting GPS Exif information in JPEGs](https://addons.mozilla.org/en-US/firefox/addon/gpsdetect)
- [Whisper & GPT-based app for passing remote SWE interviews](https://github.com/leetcode-mafia/cheetah)
- [adds back "View Image" button to Google Image Search results](https://github.com/Procyon-b/make-gis-great-again)
- https://github.com/Pondorasti/nextjs-chrome-extension
- [JShelter controls the APIs provided by the browser, restricting the data that they gather and send out to websites](https://pagure.io/JShelter/webextension/tree/main)
- https://github.com/Correia-jpv/ChatGPT-Enhanced-Conversation-History
- [Identify technology on websites.](https://github.com/AliasIO/wappalyzer)
- https://github.com/aeksco/react-typescript-chrome-extension-starter
- https://robertheaton.com/2018/05/07/making-youtube-less-bad-for-you-using-css
- https://mmazzarolo.com/blog/2019-01-13-another-tab
- https://github.com/olsh/Feedly-Notifier
- https://github.com/emragins/chrome-azure-devops
- [A keyboard interface to the web, inspired by Kakoune](https://github.com/alexherbo2/krabby)
- https://github.com/acorn/twitter-bookmarks-search
- https://github.com/Kiwka/urban-dictionary-chrome-extension
- [Generate a .sketchpalette file from any dribbble shot's color palette to be loaded in Sketch-Palette plugin.](https://github.com/amiechen/dribbble-sketch-palette)
- [Puts an RSS/Atom subscribe button back in URL bar](https://github.com/shgysk8zer0/awesome-rss)
- https://www.amie-chen.com/blog/making-paid-extension
- https://www.notion.so/Day-4-The-Danger-of-Chrome-Extensions-af93b84006ed48c18b807f512b6c0a07
- [Reader Mode](https://twitter.com/ryzalyusoff/status/1195613015837687808)
- https://www.onaralili.com/posts/maliciousbrowserextension + https://www.onaralili.com/posts/browser-extension-threat-modeling
- [SplitUp! is a browser extension allows a user to split tabs into a different window, save session, export tabs, supports multiple screens, dark mode etc.](https://github.com/onaralili/SplitUp)
- https://github.com/learn-anything/firefox-extensions
- https://github.com/learn-anything/chrome-extensions
- https://github.com/stefanbuck/awesome-browser-extensions-for-github
- https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo
- [An HTTP Web Server for Chrome (chrome.sockets API)](https://github.com/kzahel/web-server-chrome)
- https://github.com/janodvarko/webext-websocket-monitor
- [Chromebook app for forwarding connections from/to different ports and interfaces (or to internal android IP)](https://github.com/kzahel/connection-forwarder)
- [Custom keyboard shortcuts](https://github.com/mikecrittenden/shortkeys)
- [Discover hidden debugging parameters and uncover web application secrets](https://github.com/devploit/debugHunter)
- [augments your ChatGPT prompts with web results](https://github.com/qunash/chatgpt-advanced)
- https://github.com/pandawing/node-chrome-web-store-item-property
- https://github.com/infokiller/web-search-navigator
- [Browser Extension to full-text search your browsing history & bookmarks.](https://github.com/WorldBrain/Memex)
- [Open Graph Preview - How people will see your site in the most popular social networks](https://chrome.google.com/webstore/detail/open-graph-preview/ehaigphokkgebnmdiicabhjhddkaekgh)
- [Open New Tab, and write down every piece of your thought!](https://github.com/wildskyf/tab-notes)
- https://shubhapradha.github.io/30daybookmarks
- https://chrome.google.com/webstore/detail/seo-search-simulator-by-n/edfjfgjklednkencfhnokmkajbgfhpon
- [Browser extension to find SVGs on a webpage and download or copy to clipboard](https://github.com/rossmoody/svg-gobbler)
- https://chrome.google.com/webstore/detail/earth-view-from-google-ea/bhloflhklmhfpedakmangadcdofhnnoh
- [A browser extension to quickly fill shopping carts with electronic components](https://github.com/kitspace/1clickBOM)
- https://github.com/joachimesque/humanstxt-webextension
- [Image to text chrome extension](https://github.com/fxnoob/image-to-text) + https://youtu.be/27vNfF-K52c
- [Chrome extension to minimize the UI of YouTube.](https://github.com/AjayRajGvr/Minimal-YTube)
- [I am wondering why es modules are not well supported when building @ChromiumDev extensions?](https://twitter.com/daKmoR/status/1231357595358842880)
- [😷 A browser extension that puts masks on faces on the internet.](https://github.com/moklick/face-mask-browser-extension)
- [An extension to check if .git is exposed in visited websites.](https://github.com/davtur19/DotGit)
- [SourceKit for Safari is a browser extension for GitHub, that enables IDE features on your browser such as symbol navigator, go to definition and documentation on hover.](https://github.com/kishikawakatsumi/SourceKitForSafari)
- [Zoom Redirector is a browser extension that transparently redirects any meeting links to use Zoom's browser based web client.](https://news.ycombinator.com/item?id=22659216)
- A Chrome extension static analysis tool to help aide in security reviews: [repo](https://github.com/mandatoryprogrammer/tarnish) + [blog post](https://www.kitploit.com/2019/10/tarnish-chrome-extension-static.html)
- https://thehackerblog.com/kicking-the-rims-a-guide-for-securely-writing-and-auditing-chrome-extensions/index.html
- https://github.com/theajack/disable-devtool
- [Be able to use developer tools again](https://github.com/Andrews54757/Anti-Anti-Debug)
- [IE Tab exactly emulates IE by using the IE rendering engine directly within Chrome.](https://chrome.google.com/webstore/detail/ie-tab/hehijbfgiekmjfkfjpbkbammjbdenadd)
- [Browser extension that replaces the new tab page with Anki flashcards](https://github.com/corollari/ankiTab)
- [A tool that transforms Firefox browsers into a penetration testing suite](https://github.com/mazen160/Firefox-Security-Toolkit)
- https://github.com/aaronjanse/dns-over-wikipedia
- https://github.com/makaroni4/youtube_time_tracker
- [VoiceFiller Speech To Text for Website Forms](https://chrome.google.com/webstore/detail/voicefiller-speech-to-tex/mgafhkmkdcbkjajcblfijmlpiknfhffl/)
- [Google Chrome Extension. Record All Browsing in Screenshots & Full Text.](https://github.com/idibidiart/AllSeeingEye)
- [A Chrome extension to provide a QR code of the current Page Url.](https://github.com/SgiobairOg/qrer)
- [Core Web Vitals Chrome extension measures: Largest ContentFull Paint, First Input Delay, Cumulative Layout Shift](https://github.com/GoogleChrome/web-vitals-extension#web-vitals-chrome-extension-alpha)
- https://github.com/vinothsparrow/iframe-broker + https://github.com/Sjord/messpostage
- [WorldBrain's Memex: Bookmarking for the power users of the web](https://news.ycombinator.com/item?id=23227186)
- [A Firefox add-on to strip Google search results of 'blacklisted' URLs](https://news.ycombinator.com/item?id=23295989)
- [Follow blogs, wikis, YouTube channels, as well as accounts on Twitter, Instagram, etc. from a single page.](https://github.com/kickscondor/fraidycat)
- [Puppeteer recorder is a Chrome extension that records your browser interactions and generates a Puppeteer script.](https://github.com/checkly/puppeteer-recorder)
- [Keyboard glee for your web.](https://github.com/glee/glee)
- [Hunt the most starred projects on any date on GitHub.](https://github.com/kamranahmedse/githunt)
- [Google Chrome translation extension.](https://github.com/artemave/translate_onhover)
- [Awesome Screenshot Minus](https://github.com/rojer/a-s-minus)
- https://zonksec.com/blog/chrome-extension-to-detect-fake-tweets
- [Instant Data Scraper extracts data from web pages and exports it as Excel or CSV files](https://chrome.google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah)
- https://chrome.google.com/webstore/detail/mercury-reader/oknpjjbmpnndlpmnhmekjpocelpnlfdi
- https://www.i-dont-care-about-cookies.eu
- [Search the information available on a webpage using natural language instead of an exact string match](https://github.com/model-zoo/shift-ctrl-f)
- https://chromeextensionkit.com + https://news.ycombinator.com/item?id=24423023
- [Chrome extension that helps you learn a language without even trying.](https://jointoucan.com)
- [Really simple and secure ads blocking for Chrome](https://github.com/petrkle/block-it-yourself)
- https://mmazzarolo.com/blog/2020-08-29-jira-express
- [Chrome extension to track the activities of your favorite web novels](https://github.com/l-lin/wn-tracker-chrome) + https://github.com/l-lin/wn-tracker-api
- https://github.com/jiripospisil/chrome-ext-downloader
- [Create modern cross-browser extensions with no build configuration](https://github.com/cezaraugusto/extension-create)
- [Posta is a tool for researching Cross-document Messaging communication. It allows you to track, explore and exploit postMessage vulnerabilities, and includes features such as replaying messages sent between windows within any attached browser.](https://github.com/benso-io/posta)
- [A boilerplate project to quickly build a Chrome extension using TypeScript and React (built using webpack).](https://github.com/martellaj/chrome-extension-react-typescript-boilerplate)
- [Screenity is a feature-packed screen and camera recorder for Chrome](https://github.com/alyssaxuu/screenity)
- [Manage tabs, bookmarks, your browser history](https://github.com/alyssaxuu/omni)
- [Transform all your mailto and tel link in a beautiful modal with more possibilities! Open directly Gmail, Outlook and Yahoo for emails; Telegram, WhatsApp or Skype for phone numbers.](https://github.com/manzinello/mailgo)
- https://github.com/iamadamdev/bypass-paywalls-chrome + https://github.com/iamadamdev/bypass-paywalls-firefox
- [The missing star history graph of github repos](https://github.com/timqian/star-history)
- [Extension to block Service Workers registration in Chrome](https://github.com/clod81/block_service_workers)
- [Chrome Extension to export all accessible cookies of the current Tab](https://github.com/cookiengineer/me-want-cookies)
- [Spectroscope, identifies resources which are exempt from default protections enabled in Google Chrome (Cross-Origin Read Blocking, SameSite cookies) and which can be embedded cross-site.](https://chrome.google.com/webstore/detail/spectroscope/idppnaadbabknjeaifkegolcciafchpp)
- https://github.com/juanlizarazo/a-better-linkedin-chrome-extension
- [Firefox Voice is a browser extension that allows you to give voice commands to your browser](https://github.com/mozilla-extensions/firefox-voice) + https://news.ycombinator.com/item?id=24040539
- [ArchiveFox is a Firefox extension developed to use ArchiveBox without leaving the browser.](https://github.com/layderv/archivefox)
- https://github.com/dkthehuman/extension-starter-kit
- [Between Simplified Chinese (ZH-CN or GB2312) and Traditional Chinese (ZH-TW or BIG5)](https://github.com/DoctorLai/Simplified-and-Traditional-Chinese)
- https://github.com/giuseppeg/is-nextjs-site-extension
- [Track changes in a specific tab and get a notification when something happens](https://github.com/impronunciable/domification)
- [A Chrome Extension to export all words from a Memrise course to a CSV file.](https://github.com/raineorshine/memrise-export)
- [Chrome extension that allows you to monitor, browse and filter all DOM changes.](https://github.com/kdzwinel/DOMListenerExtension)
- [Chrome extension for easily manipulating URL query parameters, written in Elm.](https://github.com/OliverJAsh/chrome-query-params)
- [WebExtension that adds ability search all your bookmarked tweets!](https://github.com/flybayer/twitter-bookmarks-search)
- [DuckDuckGo Privacy Essentials](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg)
- https://charliegerard.dev/project/dark-mode-clap-extension
- https://parsiya.net/blog/2021-04-30-testing-extensions-in-chromium-browsers-nordpass + https://twitter.com/CryptoGangsta/status/1388253367395225602
- [Chrome extension recommends local businesses while shopping on Amazon or eBay](https://chrome.google.com/webstore/detail/buy-nearby/egoikpnpdihpdfenconkdnndbnhcfmkj) + https://news.ycombinator.com/item?id=27086582
- [Firefox extension for a button that temporarily disables your proxy settings (Quick Proxy Toggle)](https://bitbucket.org/delan/togpac)
- [Chrome extension that will help Romanian driving license learners to pass their exam.](https://github.com/70mmy/drpciv-helper)
- https://news.ycombinator.com/item?id=27327892 + [Many temptations of an open-source chrome extension developer](https://github.com/extesy/hoverzoom/discussions/670)
- https://github.com/raxod502/github-email-backlog
- [Find secrets that leak into JavaScript, as well as sensitive files exposed like like .git or .env](https://github.com/trufflesecurity/Trufflehog-Chrome-Extension) + https://trufflesecurity.com/blog/trufflehog-the-chrome-extension
- [Kanban style New Tab Page extension with your bookmarks and powerful search](https://github.com/d3ward/b2ntp)
- https://github.com/NekitCorp/chrome-extension-svelte-typescript-boilerplate
- [I wanted to see how much time I was spending on each website and set limits for certain ones.](https://github.com/cupcakearmy/ora)
- [Forces Apple docs to open in Objective-C](https://github.com/dimitarnestorov/apple-docs-force-default-language) + https://twitter.com/dimitarnestorov/status/1280734520891912192
- [A tweak that enables iOS safari to load chrome extensions](https://github.com/xuan32546/iOS-Safari-Extension)
- https://github.com/mhadidg/refined-linkedin-feed
- [This extension attempts to make Google Images look and feel like it did before they changed everything on August 6th, 2019](https://github.com/fanfare/googleimagesrestored)
- [ClearURLs is an add-on based on the new WebExtensions technology and will automatically remove tracking elements from URLs to help protect your privacy](https://github.com/ClearURLs/Addon)
- [web surfing copilot by enhancing your browsing history, improving your web exploration experience, and integrating with your knowledge base](https://beepb00p.xyz/promnesia.html)
- [A High-Fidelity Web Archiving Extension for Chrome and Chromium based browsers](https://github.com/webrecorder/archiveweb.page)
- https://github.com/albertz/chrome-ext-google-takeout-downloader
- https://github.com/eloquence/freeyourstuff.cc
- https://github.com/felladrin/linkedin-autoconnect-chrome-extension
- [A blazing fast & offline frontend playground](https://github.com/chinchang/web-maker)
- https://github.com/ffmpegwasm/chrome-extension-app
- https://github.com/gordalina/gmail-unsubscribe
- [Add support for a StreamDeck to Google Meet using WebHID](https://github.com/petele/StreamDeck-Meet)
- https://github.com/mattchep/bofa-allow-paste-extension
- https://github.com/jsjoeio/timezoner-extension
- [Fill in login forms using an OpenPGP-enabled smart card](https://github.com/fmeum/smart-pass)
- [Import .ics files into Google Calendar with only two clicks](https://github.com/fmeum/ics2gcal)
- https://github.com/Anarios/return-youtube-dislike
- https://github.com/tombaranowicz/BetterNewTab
- [Export Google Chrome bookmarks into markdown files](https://github.com/lubien/bookmarker)
- [Sign transactions with your private keys securely from within the browser without ever exposing them](https://github.com/GetScatter/ScatterWebExtension)
- https://github.com/zach-adams/downloads-overwrite-already-existing-files
- https://dexonline.ro/static/download/dex-ff.xpi + https://addons.mozilla.org/ro/firefox/addon/dexonline
- https://github.com/jemmaissroff/natgeo-chrome-extension
- [Test your fonts across the web by easily overriding fonts on any webpage](https://github.com/arrowtype/type-x)
- https://github.com/ansh/bionic-reading
- https://github.com/elight/slack_emoticon_inhaler
- [Browser extension that adds a table of contents to GitHub repos, wikis and gists](https://github.com/arthurhammer/github-toc)
- [Translate Japanese by hovering over words](https://github.com/birchill/10ten-ja-reader)
- [Remove the algorithmic content from Twitter, hide news & trends, lets you control which shared tweets appear on your timeline](https://github.com/insin/control-panel-for-twitter)
- [Automatically fill out cookie popups based on your preferences](https://github.com/cavi-au/Consent-O-Matic)
- [Search the textual content of any YouTube video](https://github.com/masasron/Video-Search-For-YouTube)
- [Chrome extension to detect possible xsleaks](https://github.com/1lastBr3ath/XSleaks)
- https://addons.mozilla.org/en-US/firefox/addon/firefox-translations + https://blog.mozilla.org/en/mozilla/local-translation-add-on-project-bergamot
- [A browser extension to display ChatGPT response alongside Google Search results](https://github.com/wong2/chat-gpt-google-extension) + https://news.ycombinator.com/item?id=33853773
- https://github.com/0xdevalias/chrome-NewWindowWithTabsToRight
- https://github.com/Norfeldt/github-issue-reactions-browser-extension
- [Firefox extension to highlight and save text from the web](https://github.com/frnsys/hili)
- [A browser extension to detect website censorship methods as you surf](https://github.com/KarimPwnz/censorship-detector)
- [removes ads and unwanted content from your LinkedIn feed](https://github.com/5Diraptor/CleanUp-LinkedIn-Chrome-Extension)
- https://github.com/lapcat/SafariExtensions
- Ensure paste isn’t blocked on any textbox: https://github.com/jswanner/DontF-WithPaste, https://underpassapp.com/StopTheMadness
- [Firefox 115 can silently remotely disable my extension on any site](https://lapcatsoftware.com/articles/2023/7/1.html)
- [Changes your User-Agent header to throw off tracking](https://github.com/NoraCodes/randomua)
- [A browser extension that redirects popular sites to alternative privacy friendly frontends](https://github.com/libredirect/browser_extension)
- https://cascaspace.substack.com/p/optimizing-performance-how-our-extension
- https://github.com/da2x/amp2html

# Chrome

- https://github.com/Eloston/ungoogled-chromium
- https://kayce.basqu.es/portfolio
- [When testing your redirects with Chrome, always test a 302 before a 301](https://twitter.com/Nick_Craver/status/1190228229979877378)
- https://github.com/jbranchaud/til#chrome
- [Create HAR files from Chrome Debugging Protocol data.](https://github.com/sitespeedio/chrome-har)
- [Output a video file from screenshot frames within a Chrome DevTools JSON trace file.](https://github.com/justinribeiro/devtools-to-video)
- [This tool downloads, installs, and configures a shiny new copy of Chromium.](https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2017/march/autochrome)
- [Harden your Chrome browser via enterprise policy.](https://github.com/mandatoryprogrammer/ChromeGalvanizer)
- https://blittle.github.io/chrome-dev-tools + https://github.com/blittle/chrome-dev-tools
- [Extract relative urls from a heap snapshot](https://github.com/smiegles/extract-relative-url-heapsnapshot)
- [A tool to capture communication between Chromium processes on Windows in real-time using Wireshark, by capturing data sent over named pipes.](https://github.com/tomer8007/chromium-ipc-sniffer)
- [Hidden Features of Chrome DevTools](https://martinheinz.dev/blog/33)
- https://www.mattzeunert.com/2016/03/17/devtools-never-pause-here.html
- [The feature was launched as AMP Stories, which has now been rebranded to Web Stories.](https://news.ycombinator.com/item?id=25377695)
- https://github.com/IAIK/ChromeZero
- [Web Captioner makes your event, speech, classroom lecture, or church service accessible with real-time captioning.](https://webcaptioner.com)
- [How to get sites you use daily out of your browser](https://twitter.com/cramforce/status/1385369724662403072)
- [Getting Started With Chrome DevTools Protocol](https://github.com/aslushnikov/getting-started-with-cdp)
- https://github.com/ip2k/I-Dont-Care-About-HSTS-For-Localhost

# Brave

- https://rudism.com/the-brave-browser-is-brilliant
- https://github.com/iharh/notes/tree/master/security/tracking

# Firefox

- https://madaidans-insecurities.github.io/firefox-chromium.html
- [making Firefox stop polluting your Burp session with superfluous requests](https://www.blackhillsinfosec.com/towards-quieter-firefox) + https://twitter.com/egyp7/status/1196497265743056898
- [An ongoing comprehensive user.js template for configuring and hardening Firefox privacy, security and anti-fingerprinting.](https://github.com/ghacksuserjs/ghacks-user.js)
- [Listing changes in Firefox default preferences. The diffs are created using 64-bit Firefoxes (en-US) on Windows.](https://github.com/earthlng/FFprefs-diffs)
- https://blog.mozilla.org/data/2020/03/16/understanding-default-browser-trends
- https://honzajavorek.cz/blog/how-i-consume-content
- https://timvisee.com/blog/firefox-tricks-quantumbar
- https://nelsonslog.wordpress.com/2021/12/07/firefox-compat-hacks
- https://nelsonslog.wordpress.com/2021/12/22/faking-geolocation-in-firefox
- [Separate Firefox Dark UI theme from website dark mode](https://twitter.com/darek_kay/status/1468171089796911109)
- https://github.com/MrOtherGuy/firefox-csshacks
- https://endler.dev/2024/the-dying-web

# Federated Credential Management API (FedCM)

- https://textslashplain.com/2023/04/12/auth-flows-in-a-partitioned-world

# Contact Picker API

- https://evilmartians.com/chronicles/dont-wait-lets-use-browser-contact-picker-api-now

# Geolocation API

- https://daniel.fone.net.nz/blog/2020/09/14/geolocation-api-demo

# Historic

- https://webinista.com/updates/flash-end-of-life + https://twitter.com/mattmay/status/1344728355912880129 + http://blog.archive.org/2020/11/19/flash-animations-live-forever-at-the-internet-archive
- [Last publicly available revision of the world's first web browser](https://github.com/cynthia/WorldWideWeb)
- https://brucelawson.co.uk/2022/ie-rip-or-brb
- [Comparison of Web Browsers](https://eylenburg.github.io/browser_comparison.htm)
- [History of Web Browser Engines from 1990 until today](https://eylenburg.github.io/browser_engines.htm)

# Safari

- [In my app when a user clicks play, I remove all audio elements, swap them with fresh ones, and attempt to autoplay for the user.](https://twitter.com/RogersKonnor/status/1453596502098644994) + https://github.com/cableready/audio_operations
- https://predr.ag/blog/debugging-safari-if-at-first-you-succeed
- [Safari releases are development hell](https://www.construct.net/en/blogs/ashleys-blog-2/safari-releases-development-1616)

# Staybl

- [A browser for Parkinson’s patients, with “customizable tremor compensation tremor compensation, high-contrast design, a particularly legible font, and general ease of use.”](staybl.app)

# Opera

- [Standalone client for proxies of Opera VPN](https://github.com/Snawoot/opera-proxy)
- https://medium.com/@renwa/opera-browser-vpn-bypass-20877aaf08c0

# Cookie

- [SameSite=Lax](https://twitter.com/RenwaX23/status/1206475064125853696)
- https://www.troyhunt.com/promiscuous-cookies-and-their-impending-death-via-the-samesite-policy
- https://blog.reconless.com/samesite-by-default
- [Stealing Session Cookies with Tcpdump](https://nullprogram.com/blog/2016/06/23)
- [How to Store Session Tokens in a Browser (and the impacts of each)](https://blog.ropnop.com/storing-tokens-in-browser)
- https://rudism.com/cookie-monster
- [Browser fingerprinting via favicon!](https://github.com/jonasstrehle/supercookie)
- [Exploring the SameSite cookie attribute for preventing CSRF](https://simonwillison.net/2021/Aug/3/samesite)
- https://github.com/defaultnamehere/cookie_crimes
- https://jub0bs.com/posts/2021-01-29-great-samesite-confusion
- https://github.com/iangcarroll/cookiemonster
- https://github.com/SoheilKhodayari/same-site-wiki + https://twitter.com/Soheil__K/status/1526970587083681792
- https://blog.daviddworken.com/posts/same-site-cross-origin
- [cookie tossing leading to session fixation](https://twitter.com/jub0bs/status/1563080334727839746)

# IndexDB

- https://patrickbrosset.com/articles/2023-01-17-web-storage
- https://twitter.com/tgroshon/status/1332499610192015362
- https://just-be.dev/posts/export-import-indexeddb
- https://fingerprintjs.com/blog/indexeddb-api-browser-vulnerability-safari-15
- [Why IndexedDB is slow and what to use instead](https://rxdb.info/slow-indexeddb.html)
- [Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.](https://github.com/localForage/localForage)
- [Parses Indexeddb files - used to extract devtools console history](https://github.com/phl4nk/devtoolreader)
- https://tantaman.com/2022-05-13-large-local-storage.html
- https://github.com/stars/jnv/lists/storage

# Federated Learning of Cohorts

- https://seirdy.one/2021/04/16/permissions-policy-floc-misinfo.html
- https://brave.com/why-brave-disables-floc + https://github.com/brave/brave-core/pull/8468
- https://dev.to/sgolovine/opt-your-netlify-vercel-or-github-pages-site-out-of-google-s-floc-network-3nhl
- https://amifloced.org
- https://make.wordpress.org/core/2021/04/18/proposal-treat-floc-as-a-security-concern
- https://plausible.io/blog/google-floc
- https://vivaldi.com/blog/no-google-vivaldi-users-will-not-get-floced
- https://paramdeo.com/blog/opting-your-website-out-of-googles-floc-network + https://twitter.com/tomayac/status/1383337100041359365
- https://spreadprivacy.com/block-floc-with-duckduckgo

# Content Security Policy (CSP)

- https://twitter.com/manicode/status/1371849647468208130
- https://twitter.com/mikewest/status/1370394397267869699
- [Next level anti-debugging technique using SourceMappingURL feature](https://twitter.com/WeizmanGal/status/1207355263491149825)
- https://github.com/nico3333fr/CSP-useful
- https://csper.io/blog/other-csp-security
- https://www.secjuice.com/hiding-javascript-in-png-csp-bypass + https://twitter.com/Menin_TheMiddle/status/1244325611440615426
- https://tldrsec.com/blog/content-security-policy-going-from-idea-to-afterthought
- https://sensepost.com/blog/2021/from-500-to-account-takeover + https://twitter.com/XssPayloads/status/1376389308207226881
- https://twitter.com/blipsofadoug/status/1125223582974533633
- https://threatnix.io/blog/exploiting-csp-in-webkit-to-break-authentication-authorization
- https://www.bryanbraun.com/2021/08/10/allowing-inline-scripts-in-your-content-security-policy-using-a-hash
- https://octagon.net/blog/2022/05/29/bypass-csp-using-wordpress-by-abusing-same-origin-method-execution
- [Discover new target domains using Content Security Policy](https://github.com/edoardottt/csprecon)
- https://github.com/naugtur/CSP-exercise
- [Monorepo for CSP-related packages](https://github.com/frux/csp)
- [XSS with CSP bypass leads to diagrams backdoor in jgraph/drawio](https://archive.li/XSvGv) + https://huntr.dev/bounties/4c1c5db5-210f-4d7e-8380-b95f88fdb78d
- https://engineering.linkedin.com/blog/2023/enhancing-security-and-developer-productivity--linkedin-s-journe

# Cross-origin resource sharing (CORS)

- https://github.com/monsur/enable-cors.org
- https://www.kitploit.com/2019/12/corstest-simple-cors-misconfiguration.html
- [Authenticated CORS with Access-Control-Allow-Origin: \*](https://blog.bi.tk/chrome-cors)
- https://github.com/RUB-NDS/CORStest
- https://ieftimov.com/post/deep-dive-cors-history-how-it-works-best-practices
- https://github.com/onsecru/cors_playground
- [Cache your CORS, for performance & profit](https://httptoolkit.tech/blog/cache-your-cors)
- https://jeffy.info/2019/07/22/exposing-cors-headers.html
- https://medium.com/@mashoud1122/cors-misconfiguration-account-takeover-out-of-scope-to-grab-items-in-scope-66d9d18c7a46
- https://github.com/mscoutermarsh/cors-test
- https://w3c.github.io/webappsec-cors-for-developers

# Cross-Origin-Opener-Policy (COOP)

- [COOP and COEP explained](https://docs.google.com/document/d/1zDlfvfTJ_9e8Jdc8ehuV4zMEu9ySMCiTGMS9y0GU92k)
- https://blog.daviddworken.com/posts/stopping-xs-leaks-at-scale + https://github.com/mjz3/LeakuidatorPlus + https://twitter.com/ndevtk/status/1549894289865560065
- [Cross-origin isolation (COOP and COEP) through a service worker for situations in which you can't control the headers (e.g. GH pages)](https://github.com/gzuidhof/coi-serviceworker)

# Same Origin Policy (SOP)

- https://parsiya.net/blog/2020-11-01-the-same-origin-policy-gone-wild
- https://github.com/rafaybaloch/SOP-Bypass-Mini-Test-Suite

# Search Engine Optimization (SEO)

- https://www.smashingmagazine.com/smashing-guide-search-engine-optimization
- https://developers.google.com/search/docs/guides/intro-structured-data
- [Find broken links, missing images, etc within your HTML.](https://github.com/stevenvachon/broken-link-checker)
- [Scurry around your site and find all those broken links](https://github.com/JustinBeckwith/linkinator)
- https://vasco3.gitbooks.io/hacks-n-notes/content/internet_marketing/seo.html
- https://github.com/darekkay/best-practices#seo
- [Curs Super SEO pentru eCommerce](https://academia.gomag.ro/biblioteca?access=67)
- https://www.linkedin.com/pulse/200-unsolicited-seo-tips-mark-williams-cook
- [The Open Source A/B Testing Platform](https://github.com/growthbook/growthbook)
- https://ahrefs.com/blog/seo-glossary
- [SEO | knowthen](https://m.youtube.com/playlist?list=PLs0HJRuXPAqsj9fxpr8eJdJxCT2fN_G8S)
- [Today I set up SEO for rubyandrails.info](https://twitter.com/nleonid/status/1554154237080354818)
- https://github.com/sw-yx/company-youtubes#business-oriented
- [High signal information security sources Goggle](https://github.com/forcesunseen/netsec-goggle)
- https://github.com/marcobiedermann/search-engine-optimization
- https://github.com/thospfuller/awesome-search-engine-optimization
- [The potential of client-side rendered apps compared to server-side rendering](https://github.com/theninthsky/client-side-rendering)
- https://mikebifulco.com/posts/own-your-work-with-canonical-tags
- https://vercel.com/blog/how-google-handles-javascript-throughout-the-indexing-process
- [The SEO Roadmap with Free Resources & Tools](https://learningseo.io)

# Server-sent events (SSE)

- https://m.youtube.com/playlist?list=PLw5h0DiJ-9PAQ1pKeDanXUjGbjPAluT7S

# Web Audio API

- https://github.com/idevelop/google-cloud-speech-webaudio
- [iOS Safari is like IE6 when it comes to WebAudio](https://twitter.com/stoyanstefanov/status/1343833249382973442)
- [Detecting pitch with the Web Audio API and autocorrelation](https://alexanderell.is/posts/tuner)

# Web Real-Time Communication (WebRTC)

- https://github.com/adalkiran/webrtc-nuts-and-bolts
- https://siobud.com, https://github.com/webrtc-for-the-curious/webrtc-for-the-curious
- https://m.youtube.com/playlist?list=PLWIcRrPLCdUeu5vBImsX2mMBacbomDrig
- [WebRTC Boston](https://m.youtube.com/channel/UCOYrKr3E50aY5VhHey-MrzA/playlists)
- [Anyone do much with WebRTC?](https://twitter.com/tannerlinsley/status/1220121545621700609)
- [Turns a Web Browser into a Web Server with WebRTC](https://github.com/sinclairzx81/smoke)
- https://github.com/whatismyinternalip/whatismyinternalip.github.io
- [The various ways your RTC may be crushed; a presentation on RTC DoS attacks - Enable Security](https://m.youtube.com/playlist?list=PLfoovPTqAipVGa__xPSatN9qKC22nTKl7)
- https://twitter.com/iggredible/status/1300240215789821954
- [browser-based internal network scanner that detects victim's LAN IP (loops back via WebRTC)](http://samy.pl/webscan) + https://twitter.com/samykamkar/status/1329124348779667456
- [A self contained OBS -> FTL -> WebRTC live streaming server.](https://github.com/GRVYDEV/Project-lightspeed)
- [Share a terminal session over WebRTC](https://github.com/maxmcd/webtty)
- https://github.com/delapuente/presentations#webrtc--web-components
- https://github.com/kgryte/awesome-peer-to-peer#resources
- https://github.com/EnableSecurity/awesome-rtc-hacking
- [Easy P2P file transfer powered by WebRTC - inspired by Apple AirDrop](https://github.com/szimek/sharedrop)
- https://github.com/muaz-khan/WebRTC-Experiment
- https://github.com/adamavenir/talkto
- https://github.com/diafygi/webrtc-ips
- [A tool to test and exploit STUN, TURN and TURN over TCP servers](https://github.com/firefart/stunner) + https://firefart.at/post/multiple_vulnerabilities_cisco_expressway + https://www.rtcsec.com/article/slack-webrtc-turn-compromise-and-bug-bounty
- https://piranna.github.io/2021/04/23/How-to-build-WebRTC-for-Android-in-Ubuntu-21.04
- https://piranna.github.io/2020/12/30/Types-of-WebRTC-networks
- [Blender session in the browser over WebRTC](https://twitter.com/paulgb/status/1583460709538492416)
- [Karl Stolley, author of Programming WebRTC](https://forum.devtalk.com/t/spotlight-karl-stolley-author-interview-and-ama/82817)
- [Polyfill for WebRTC in Workers](https://github.com/johanholmerin/worker-webrtc)

# Canvas

- https://pqina.nl/blog/cropping-images-to-an-aspect-ratio-with-javascript
- [A simple Christmas tree.](https://github.com/anvaka/atree)
- [Screenshots with JavaScript](https://github.com/niklasvh/html2canvas)
- https://github.com/raphamorim/awesome-canvas
- https://github.com/Rich-Harris/yootils/blob/master/src/canvas/sprite.ts
- [HTML5 Canvas implementation for NodeJS backed by Puppeteer.](https://github.com/pshihn/puppet-canvas)
- https://github.com/tsayen/dom-to-image
- [The better way to render text on HTML5 Canvas](https://github.com/geongeorge/Canvas-Txt)
- https://github.com/sunify/canvas-playground
- https://github.com/desandro/practical-ui-physics
- [Canvas + JSX + Hooks](https://github.com/jchn/redraw)
- [Visual Web Development (2021) | Radu Mariescu-Istodor](https://m.youtube.com/playlist?list=PLB0Tybl0UNfb3hTHPfEIg1SPw_-Ca9iIw)
- [A library for capturing web page self screenshots](https://github.com/TomasHubelbauer/selfie)
- https://bkardell.com/blog/OffscreenCanvas.html
- https://github.com/mattdesl/workshop-generative-art
- [An Underrated Way To Learn Programming: Generative Art](https://carltheperson.com/posts/artgen)
- https://github.com/psenough/teach_yourself_demoscene_in_14_days
- [procedurally generated fish drawings](https://github.com/LingDong-/fishdraw)
- https://github.com/bubkoo/html-to-image
- https://developer.mozilla.org/en-US/blog/javascript-shape-drawing-function

# File System API

- https://developer.chrome.com/articles/origin-private-file-system

# Web Authentication API

- https://goteleport.com/blog/how-passwordless-works
- https://betterappsec.com/a-medium-dive-into-web-application-authentication-342d1d002a61
- https://denhoff.ca/posts/webauthn-by-id-android
- https://duo.com/blog/webauthn-passwordless-fido2-explained-componens-passwordless-architecture
- https://fidoalliance.org/fido2-2/fido2-web-authentication-webauthn
- https://secfense.com/blog/fido2-authentication-explained
- https://www.youtube.com/watch?v=SWocv4BhCNg + https://fidoalliance.org/passkeys
- https://nelsonslog.wordpress.com/2024/03/22/passkeys-still-awkward-in-mar-2024-android-chrome-windows-1password + https://nelsonslog.wordpress.com/2024/03/23/passkeys-try-two

# `WebGL`

- https://github.com/davidwparker/programmingtil-webgl + https://m.youtube.com/playlist?list=PLPqKsyEGhUnaOdIFLKvdkXAQWD4DoXnFl
- https://tchayen.com/brief-explanation-of-webgl
- https://www.pheelicks.com/speaking
- https://github.com/luruke/awesome-casestudy
- https://github.blog/2020-12-21-how-we-built-the-github-globe
- https://formidable.com/blog/2021/future-ui
- https://techblog.geekyants.com/recreating-real-world-terrain-with-react-threejs-and-webgl-shaders-1
- https://webglfundamentals.org + https://twitter.com/redblobgames/status/1369123816719360000
- https://alain.xyz/blog/raw-webgl
- [Minimal WebGL Library](https://github.com/oframe/ogl)
- https://github.com/brunoimbrizi/interactive-particles
- https://github.com/lesnitsky/webgl-month
- https://github.com/rezaali/webgl-tutorial
- https://github.com/rezaali/webgl-sketches
- https://github.com/stackgl/webgl-workshop
- [Javascript and the next decade of data programming](http://benschmidt.org/post/2020-01-15/2020-01-15-webgpu) + https://github.com/rofrol/awesome-wgpu + https://github.com/danbev/learning-gpgpu
- https://www.amazon.com/Learning-Three-js-JavaScript-Library-Second/dp/1784392219
- https://www.davrous.com/2020/03/22/understanding-shaders-the-secret-sauce-of-3d-engines
- [an experiment to make something like "vvvv" in javascript, html and webgl.](https://github.com/idflood/ThreeNodes.js)
- https://xem.github.io/articles/webgl-guide.html + https://twitter.com/MaximeEuziere/status/1261643172582653954
- https://github.com/spite/virtual-webcam
- https://github.com/caged/regl-learn
- https://github.com/erich666/RealTimeRendering
- https://github.com/jsulpis/realtime-planet-shader
- https://www.charlespetzold.com/blog/2024/09/Rudimentary-3D-on-the-2D-HTML-Canvas.html
- https://github.com/terkelg/awesome-creative-coding

# WebGPU

- https://hackaday.com/2022/03/09/webgpu-better-than-webgl
- [How Does a GPU Shader Core Work? | Aras Pranckevičius](https://aras-p.info/texts/files/2018Academy%20-%20GPU.pdf)
- https://cohost.org/mcc/post/1406157-i-want-to-talk-about
- https://github.com/gfxfundamentals/webgpufundamentals

# Human Interface Device (WebHID)

- https://github.com/robatwilliams/awesome-webhid

# Web MIDI

- https://github.com/obensource/web-midi-api-docs
- https://obensource.com/blogs/high-fidelity-event-sampling-and-playback-with-vanilla-javascript

# `WebUSB`

- https://github.com/webusb/awesome
- https://charliegerard.dev/blog/aircraft-radar-system-rtl-sdr-web-usb
- https://charliegerard.dev/blog/replay-attacks-javascript-hackrf

# Headless

- [Node library to automate Chromium, Firefox and WebKit browsers](https://github.com/microsoft/playwright) + [opinion](https://twitter.com/xopek59/status/1221460300387573760) + https://medium.com/@woff/arbitrary-file-read-tricks-with-headless-browsers-eeebc2d9e5c8
- [Comparing Cypress and Puppeteer](https://swatinem.de/blog/cypress-puppeteer)
- [Capture screenshots in multiple browsers!](https://github.com/juliangruber/capture-screenshot)
- [Puppeteer example scripts for running Headless Chrome from Node.](https://github.com/checkly/puppeteer-examples)
- https://blog.checklyhq.com/cypress-vs-selenium-vs-playwright-vs-puppeteer-speed-comparison
- [A Headless Chrome rendering solution](https://github.com/GoogleChrome/rendertron)
- https://github.com/humanwhocodes/puppeteer-data-extractor
- http://blog.ezyang.com/2021/11/interactive-scraping-with-jupyter-and-puppeteer

# Performance

- https://github.com/leandrotk/web-performance-studies
- [interactive flamegraph visualizer](https://github.com/jlfwong/speedscope)
- https://www.speedcurve.com/blog/element-timing-one-true-metric
- https://www.webpagetest.org/learn/lightning-fast-web-performance/#toc
- https://www.davrous.com/2020/03/20/frame-variable-refresh-rates-or-why-tesla-is-responsible-for-the-60-fps-war
- https://ethanmarcotte.com/wrote/au-revoir-mon-ampmour
- [A Node.js command line tool that crawls a domain and gathers lighthouse performance data for every page.](https://github.com/cloudfour/lighthouse-parade)
- [The Almost-Complete Guide to Cumulative Layout Shift](https://jessbpeck.com/posts/completecls)
- https://webvitals.dev/cls
- [Web Performance Recipes With Puppeteer](https://addyosmani.com/blog/puppeteer-recipes)
- https://calibreapp.com/tools/core-web-vitals-checker
- [A curated list of Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo)
- https://3perf.com/talks/web-perf-101
- https://blog.webpagetest.org/posts/test-your-spa
- https://www.stefanjudis.com/blog/how-to-find-all-render-blocking-resources-with-javascript
- [SingleFile was really slow on pages with large stylesheets, especially in Firefox](https://twitter.com/check_ca/status/1583927164956995585)
- [effective ways to improve Core Web Vitals performance in 2023](https://web.dev/top-cwv-2023)
- [Cumulative Layout Shift Differences](https://www.debugbear.com/blog/cls-lab-field-differences)
- https://dev.to/noamr/when-a-millisecond-is-not-a-millisecond-3h6
- https://web.dev/shopping-for-speed-on-ebay
- https://www.jovidecroock.com/blog/browser-timings
- https://www.iamtk.co/leveraging-the-idle-until-urgent-technique-to-improve-performance, https://github.com/imteekay/web-performance-research
- Interaction to Next Paint (INP)
  - https://www.speedcurve.com/blog/INP-user-experience-correlation
- First Input Delay (FID)
  - 

# Miscellaneous

- [Web Browser Engineering](https://github.com/browserengineering/book) + https://courses.cs.washington.edu/courses/cse490x/22sp/lecture +
- https://wiki.systemcrafters.net/guix/browsers
- https://github.com/vasanthk/how-web-works
- [The End of Indie Web Browsers: You Can (Not) Compete.](https://news.ycombinator.com/item?id=21992050)
- [Shareable bookmarks.](https://github.com/darekkay/static-marks)
- https://textslashplain.com/2020/02/09/demystifying-browsers + https://textslashplain.com/2020/09/29/debugging-browsers-tools-and-techniques
- https://github.com/trimstray/the-book-of-secret-knowledge#black_small_square-browsers-1
- https://alan.norbauer.com/articles/browser-debugging-tricks
- https://textslashplain.com/2020/09/25/web-debugging-watching-element-changes
- https://github.com/styfle/breaking-changes-web
- [QR codes art](https://research.swtch.com/qart)
- https://github.com/dongri/emv-qrcode-doc
- https://github.com/azu/browser-resources

# Tool

- [rrweb is an open source web session replay library, which provides easy-to-use APIs to record user's interactions and replay it remotely.](https://github.com/rrweb-io/rrweb)
- https://github.com/captainbrosset/devtools-tips
- [estimating the % of web users that have certain web features natively supported](https://github.com/paulirish/web-feature-availability)
- [From a Formal Model to the Automatic Evaluation of Cross-Site Leaks in Web Browsers](https://github.com/RUB-NDS/xsinator.com)
- https://github.com/iipc/awesome-web-archiving
- [using ForensiX to extract information about a Chrome dump](https://iosifache.me/posts/forensix-walktrough)

# WebCryptoAPI

- https://docs.google.com/presentation/d/1LbJcPulQ_a4utqNCUoGCk8GTQbchN2BL_kAF3DNJQbo
- https://blog.intothesymmetry.com/2020/01/the-curious-case-of-webcrypto-diffie.html
- https://github.com/diafygi/webcrypto-examples
- [Bring your own filesystem, a javascript library that allows users to connect their own data storage backend to your webapp](https://github.com/diafygi/byoFS)
- [Embed any file into an encrypted, self-decrypting HTML file](https://github.com/fmeum/polysafe)
- https://github.com/mprimi/portable-secret
- https://github.com/Metalnem/javascript-crypto
- https://github.com/robinmoisson/staticrypt/pull/111/files
