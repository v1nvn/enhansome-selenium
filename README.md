# Awesome Selenium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 437,047 | 🐛 69 | 📅 2026-01-28 [![Test Awesome List](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml/badge.svg)](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml) ⭐ 1,111 | 🐛 0 | 📅 2025-01-03 with stars

> A curated list of delightful [Selenium](http://www.seleniumhq.org/) [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 437,047 | 🐛 69 | 📅 2026-01-28 list thing.

## Resources

* [Tools](#tools)
* [CSS Regression Testing](#css-regression-testing)
* [Containers](#containers)
* [Driver](#driver)
* [Desktop Tools](#desktop-tools)
* [Selenium Grid](#selenium-grid)
* [Cloud Services](#cloud-services)
* [Device Farms](#device-farms)
* [Web Scraping / Mining](#web-scraping--mining)
* [Specifications](#specifications)
* [Blogs](#blogs)

### Tools

#### Javascript

* [selenium-webdriver](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) ⭐ 34,005 | 🐛 212 | 🌐 Java | 📅 2026-02-13 - The official WebDriver JavaScript bindings from the Selenium project.
* [WD](https://github.com/admc/wd) ⭐ 1,524 | 🐛 72 | 🌐 JavaScript | 📅 2024-02-13 - WebDriver/Selenium 2 node.js client.
* [WebdriverIO](http://webdriver.io) - better implementation of WebDriver bindings with predefined 50+ actions.
* [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing.
* [SlimerJS](http://slimerjs.org/) - A scriptable browser for Web developers.
* [Nightwatch](http://nightwatchjs.org/) - efficient and straightforward Javascript End-to-End tests.
* [Karma](http://karma-runner.github.io/0.12/index.html) - Brings a productive testing environment to developers for unit testing (mostly AngularJS).
* [Protractor](https://angular.github.io/protractor/) - Protractor is an end-to-end test framework for AngularJS applications.
* [CodeceptJS](http://codecept.io/) - Modern Era Acceptance Testing Framework for NodeJS.

#### Ruby

* [Anemone](https://github.com/chriskite/anemone) ⭐ 1,610 | 🐛 51 | 🌐 Ruby | 📅 2020-03-20 - Anemone web-spider framework.
* [Spidr](https://github.com/postmodern/spidr) ⭐ 833 | 🐛 16 | 🌐 Ruby | 📅 2026-01-12 - web spidering library that can spider a site, multiple domains, certain links or infinitely.
* [Selenium with Ruby](http://seleniumhq.github.io/selenium/docs/api/rb/index.html) - Selenium Ruby bindings
* [Watir](http://watir.github.io) - Automated testing that doesn’t hurt
* [Mechanize](http://docs.seattlerb.org/mechanize/) - automating interaction with websites.
* [cobweb](https://rubygems.org/gems/cobweb) - web crawler that can use resque to cluster crawls to quickly crawl extremely large sites.
* [Capybara](https://rubygems.org/gems/capybara) - an integration testing tool for rack based web applications. It simulates how a user would interact with a website.

#### PHP

* [Facebook WebDriver](https://github.com/facebook/php-webdriver) ⭐ 5,210 | 🐛 24 | 🌐 PHP | 📅 2026-02-07 - A PHP client for webdriver.
* [Steward](https://github.com/lmc-eu/steward) ⭐ 222 | 🐛 20 | 🌐 PHP | 📅 2024-08-16 - A test runner integrating php-webdriver with PHPUnit.
* [Selenium Setup](https://github.com/bogdananton/Selenium-Setup) ⭐ 27 | 🐛 5 | 🌐 PHP | 📅 2017-03-15 - A tool for PHP developers to start their own Selenium server.

#### Python

* [Helium](https://github.com/mherrmann/selenium-python-helium) ⭐ 8,214 | 🐛 54 | 🌐 Python | 📅 2026-02-04 - Helium makes Selenium easier and faster to use
* [Selene](https://github.com/yashaka/selene) ⭐ 725 | 🐛 170 | 🌐 Python | 📅 2025-11-25 - Selenide-inspired concise and readable automated test framework, supports Ajax well like Selenide.
* [behave-webdriver](https://github.com/spyoungtech/behave-webdriver) ⭐ 63 | 🐛 16 | 🌐 Python | 📅 2025-08-11 behavior driven testing with Selenium and Python.
* [Selenium with Python](http://selenium-python.readthedocs.io/) - Selenium Python bindings
* [mechanize](http://wwwsearch.sourceforge.net/mechanize/) - Stateful programmatic web browsing.
* [Robot](http://robotframework.org/) - Robot Framework is a generic test automation framework for acceptance testing and ATDD.

#### Java

* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager) ⭐ 2,676 | 🐛 0 | 🌐 Java | 📅 2026-02-02 - Automatic management of Selenium WebDriver binaries.
* [Selenide](https://github.com/codeborne/selenide) ⭐ 1,910 | 🐛 30 | 🌐 Java | 📅 2026-02-06 - A framework for writing easy-to-read and easy-to-maintain automated tests using a Fluent API. Selenide has a magic trick that resolves most problems with Ajax and timeouts.
* [seleniumQuery](https://github.com/seleniumQuery/seleniumQuery) ⭐ 72 | 🐛 2 | 🌐 Java | 📅 2025-07-12 - jQuery-like cross-driver interface in Java for WebDriver. Designed as a thin layer, it can be used alone or on top of your favorite framework just to make some cases (e.g. asserting/waiting) simpler when needed.
* [Lightning](https://github.com/aerokube/lightning-java) ⭐ 31 | 🐛 8 | 🌐 Java | 📅 2023-05-11 - Lightweight and lightning fast WebDriver client.
* [darcy](https://github.com/darcy-framework/darcy-webdriver) ⭐ 23 | 🐛 10 | 🌐 Java | 📅 2019-04-22 - Page object framework for structured, maintainable automation.
* [Selenium with Java](http://seleniumhq.github.io/selenium/docs/api/java/index.html) - Selenium Java bindings
* [Conductor](http://conductor.ddavison.io) - Turbo-boosted Selenium framework that makes test writing a breeze.
* [Galen Framework](http://galenframework.com/) - Automated testing of look and feel for your responsive websites.
* [Serenity](http://www.thucydides.info/) - It is an open source library for writing better quality automated acceptance tests faster. (Formerly Thucydides).

#### C\#

* [Atata](https://github.com/atata-framework/atata) ⭐ 502 | 🐛 9 | 🌐 C# | 📅 2026-02-08 - Automated web testing full featured framework based on Selenium WebDriver.
* [Strontium](https://github.com/jimevans/strontium) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2013-01-23 - A .NET implementation (but outdated) for Selenium/WebDriver (Remote) Server
* [Selenium with C#](http://seleniumhq.github.io/selenium/docs/api/dotnet/index.html) - Selenium C# bindings

#### Groovy

* [Geb](http://www.gebish.org/) - It can be used for scripting, scraping and general automation — or equally as a functional/web/acceptance testing solution via integration with testing frameworks such as Spock, JUnit & TestNG.

#### Dart

* [dart.webdriver](https://github.com/google/webdriver.dart) ⭐ 142 | 🐛 28 | 🌐 Dart | 📅 2026-02-01 - Provides WebDriver bindings for Dart. These use the WebDriver JSON interface, and as such, require the use of the WebDriver remote server.

### CSS Regression Testing

* [WebdriverCSS](https://github.com/webdriverio/webdrivercss) ⚠️ Archived - Regression testing tool for [WebdriverIO](http://webdriver.io) (currently deprecated, please use [wdio-screenshot](https://www.npmjs.com/package/wdio-screenshot) for the time being).

### Containers

#### Docker

* [SeleniumHQ/docker-selenium](https://github.com/SeleniumHQ/docker-selenium) ⭐ 8,596 | 🐛 84 | 🌐 Shell | 📅 2026-02-09 - Docker images for Selenium Standalone Server, Hub, and Node configurations with Chrome and Firefox.
* [Selenoid](https://github.com/aerokube/selenoid) ⚠️ Archived - A lightweight Selenium hub implementation launching browsers in Docker containers.
* [zalando/zalenium](https://github.com/zalando/zalenium) ⚠️ Archived - Allows anyone to have a disposable and flexible Selenium Grid infrastructure
* [elgalu/docker-selenium](https://github.com/elgalu/docker-selenium) ⚠️ Archived - Selenium in Docker with Chrome & Firefox plus video recording support.
* [Ggr](https://github.com/aerokube/ggr) ⚠️ Archived - A lightweight load balancer used to create big Selenium clusters.
* [bravostudiodev/bravo-grid](https://github.com/bravostudiodev/bravo-grid) ⭐ 5 | 🐛 2 | 🌐 Java | 📅 2018-02-28 - Docker image/setup for Selenium Grid Extras (see under Selenium Grid section), for providing remote Sikuli test/automation execution and grid node file upload/download support.

#### Kubernetes

* [kubernetes/examples](https://github.com/kubernetes/examples/tree/master/staging/selenium) ⭐ 6,542 | 🐛 12 | 🌐 Shell | 📅 2025-11-18 - Example deployment of Selenium Hub and Nodes on a Kubernetes cluster
* [Moon](https://github.com/aerokube/moon) ⭐ 268 | 🐛 83 | 🌐 HTML | 📅 2025-12-17 - A commercial closed-source enterprise Selenium implementation using Kubernetes to launch browsers
* [Callisto](https://github.com/wrike/callisto) ⭐ 116 | 🐛 6 | 🌐 Python | 📅 2026-01-15 - An open-source tool to launch browsers in Kubernetes. Separate is created for each selenium session.
* [WebGrid](https://github.com/TilBlechschmidt/WebGrid) ⚠️ Archived - An open-source, decentralized, scalable and robust selenium-grid equivalent.

### Driver

#### Desktop (browsers)

* [Firefox](https://github.com/SeleniumHQ/selenium/wiki/FirefoxDriver) ⭐ 34,005 | 🐛 212 | 🌐 Java | 📅 2026-02-13 - Firefox driver (for FF < v48) is included in the selenium-server-standalone.jar available in the downloads.
* [Internet Explorer](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver) ⭐ 34,005 | 🐛 212 | 🌐 Java | 📅 2026-02-13 - The InternetExplorerDriver is a standalone server which implements WebDriver's wire protocol.
* [Safari](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver) ⭐ 34,005 | 🐛 212 | 🌐 Java | 📅 2026-02-13 - The SafariDriver is implemented as a Safari browser extension. The driver inverts the traditional client/server relationship and communicates with the WebDriver client using WebSockets (only supported for Safari <= v9, all new Safari version comming with macOS Sierra come with an integrated SafariDriver that is closed source by Apple).
* [Geckodriver](https://github.com/mozilla/geckodriver) ⭐ 7,446 | 🐛 190 | 📅 2025-04-11 - Firefox driver (for FF > v48), supported with Selenium >= v3
* [Opera](https://github.com/operasoftware/operachromiumdriver/blob/master/README.md) ⭐ 269 | 🐛 79 | 📅 2026-01-09 - OperaDriver is a vendor-supported WebDriver implementation developed by Opera Software and volunteers that implements WebDriver API for Opera.
* [Chrome](https://sites.google.com/a/chromium.org/chromedriver/home) - ChromeDriver is a standalone server which implements WebDriver's wire protocol for Chromium.
* [Edgedriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) - Microsoft Webdriver server for Edge

#### Mobile (browsers and apps)

* [Appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps. It drives iOS, Android Apps using the WebDriver protocol.
* [Selendroid](http://selendroid.io/mobileWeb.html) - Selendroid is based on the Android instrumentation framework.
* [ios-driver](http://ios-driver.github.io/ios-driver/) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [WebDriverAgent](https://github.com/manishPatwari/WebDriverAgent) ⭐ 53 | 🐛 12 | 🌐 Objective-C | 📅 2018-12-14 - a WebDriver server for iOS to remote control devices via WebDriver API.

#### Desktop GUI Automation (non-browser-centric)

* [WinAppDriver](https://github.com/Microsoft/WinAppDriver) ⭐ 3,992 | 🐛 1,153 | 🌐 C# | 📅 2025-04-14 - Microsoft's WebDriver implementation for Windows application automation.
* [Winium](https://github.com/2gis/Winium) ⭐ 399 | 🐛 95 | 🌐 C# | 📅 2023-12-20 - Automation framework for Windows platforms. It is free. It is opensource. It is Selenium-based. Supports: Windows Desktop (WPF, WinForms); Windows Store or Universal Apps for Windows Phone; Windows Phone Silverlight Apps.
* [QtWebDriver](https://github.com/cisco-open-source/qtwebdriver) ⭐ 197 | 🐛 27 | 🌐 C++ | 📅 2022-07-06 - For using WebDriver to automate Qt-based GUI applications.
* [AutoItDriverServer](https://github.com/daluu/AutoItDriverServer) ⭐ 33 | 🐛 7 | 🌐 Python | 📅 2016-01-12 - Selenium server to control/drive AutoIt via (Remote)WebDriver API.
* [AutoPyDriverServer](https://github.com/daluu/AutoPyDriverServer) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2015-01-18 - Selenium server to control/drive AutoPy via (Remote)WebDriver API.
* [SilkAppDriver](https://github.com/MicroFocus/SilkAppDriver) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2017-10-09 - Selenium server to control/drive the commercial SilkTest platform via (Remote)WebDriver API.
* [Appium for Mac](origin/\[https:/appium.io/docs/en/drivers/mac/]\(https:/github.com/appium/appium-mac2-driver\)) - Appium/WebDriver implementation for automating Mac OS X desktop.

### Desktop Tools

* [Looking Glass](https://github.com/dmolchanenko/LookingGlass) ⭐ 54 | 🐛 3 | 🌐 Groovy | 📅 2016-11-02 - Java application that offers a cross-browser element inspector and Selenium code generator.
* [SWET](https://github.com/sergueik/SWET) ⭐ 39 | 🐛 4 | 🌐 Java | 📅 2024-10-03 - A successor to SWD Page Recorder, for the same functionality.
* [Silk WebDriver](https://www.microfocus.com/products/silk-portfolio/silk-webdriver/) - A Selenium IDE alternative for record, playback, and script export, from the creators of SilkTest.
* [Fire IE Selenium](https://code.google.com/archive/p/fire-ie-selenium/) - Microsoft Excel-based tool providing element inspection for Internet Explorer browser.

### Selenium Grid

* [SeLion](https://github.com/paypal/SeLion) ⭐ 285 | 🐛 31 | 🌐 Java | 📅 2023-11-23 - A (Java) framework for running Selenium tests with additional features beyond the basic Selenium Grid functionality, particularly like stability improvements, etc.
* [Selenium Grid Extensions](https://github.com/sterodium/selenium-grid-extensions) ⭐ 46 | 🐛 3 | 🌐 Java | 📅 2021-03-23 - A set of extensions for Selenium Grid that provide additional features like running Sikuli tests/automation remotely, upload/download files on a grid node.
* [Selenium Grid Extras](https://github.com/groupon/Selenium-Grid-Extras) - A framework that provides additional features beyond the basic Selenium Grid like video recording.

### Cloud Services

* [Sauce Labs](https://saucelabs.com) - Cross browser testing made awesome. Selenium testing, mobile testing, JS unit testing on 300+ OS/browser platforms. Get started for free.
* [HeadSpin](https://www.headspin.io/) - Test your website for cross browser compatibility on thousands of real device running real browsers. Get instant access to multiple desktop and mobile browsers on the cloud. Get Free Trial.
* [Browserstack](https://www.browserstack.com/) - Test your website for cross browser compatibility on real browsers. Instant access to multiple desktop and mobile browsers. Get Free Trial.
* [TestGrid](https://www.testgrid.io/) - End to End testing of mobile apps & websites on 1000+ real browsers & OS. Request Free Trial.
* [LambdaTest](https://www.lambdatest.com/selenium-automation) - Test your website for cross browser compatibility on 2000+ real browsers & OS. Get Free Trial.
* [TestingBot](https://testingbot.com) - TestingBot provides easy cross browser testing with Selenium in the cloud.
* [Moon Cloud](https://aerokube.com/moon-cloud/) - Your dedicated Selenium cluster in public cloud platform with per-minute billing and unlimited number of browsers.
* [Mail7](https://www.mail7.io/) - Disposable email service to automate the email workflow testing, [This document](https://docs.mail7.io/tutorials/registration-and-login-automation-using-selenium-with-disposable-email) explains how to implement Mail7 with Selenium
* [Thundra Foresight](https://www.thundra.io/foresight) - A visibility tool into your test suites by spotting test failures in no time.
* [Hyperbrowser](https://hyperbrowser.ai/) - Browser infrastructure and automation for running and scaling Selenium automations with headless Chrome with advanced features like proxies, captcha solving, and session recording.

### Device Farms

* [OpenSTF](https://github.com/DeviceFarmer/stf) ⭐ 4,307 | 🐛 172 | 🌐 JavaScript | 📅 2025-12-01 - A framework for running your own device farm, geared toward Android, but also iOS.

### Web Scraping / Mining

* [Scrapy](http://scrapy.org) - **Python**, mainly a scraper/miner - fast, well documented and, can be linked with [Django Dynamic Scraper](http://django-dynamic-scraper.readthedocs.org/en/latest/) for nice mining deployments, or [Scrapy Cloud](http://scrapinghub.com/scrapy-cloud.html) for PaaS (server-less) deployment, works in terminal or an server stand-alone process, can be used with **Celery**, built on top of **Twisted**.
* [Node-Crawler](https://github.com/sylvinus/node-crawler) ⭐ 6,784 | 🐛 30 | 🌐 TypeScript | 📅 2025-05-28 - **Node.js** Web Crawler/Spider for NodeJS + server-side jQuery.

### Specifications

* [The WebDriver Wire Protocol](https://www.selenium.dev/documentation/legacy/json_wire_protocol/) - All implementations of WebDriver that communicate with the browser, or a RemoteWebDriver server shall use a common wire protocol.
* [WebDriver](http://www.w3.org/TR/webdriver/) - This specification defines the WebDriver API, a platform and language-neutral interface and associated wire protocol that allows programs or scripts to introspect into, and control the behavior of, a web browser.

### Blogs

* [Official Selenium Blog](https://www.selenium.dev/blog/) - The official blog by SeleniumHQ.
* [Elemental Selenium](http://elementalselenium.com/) - A free, once-weekly e-mail on how to use Selenium like a Pro.
* [SauceLabs Blog](https://saucelabs.com/blog) - Blog curated by SauceLabs.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christian Bromann](http://www.christian-bromann.com/) has waived all copyright and related or neighboring rights to this work.
