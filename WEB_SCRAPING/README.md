# Web scraping example using NodeJS, and Puppeteer
## About Puppeteer
Puppeteer is a Node library which provides a high-level API to control Chrome or Chromium over the DevTools Protocol. Puppeteer runs headless by default, but can be configured to run full (non-headless) Chrome or Chromium.

## What does the given example do?
It is a REST API built on ExpressJS, which accepts the username of a user, and the sitename (Hackerearth, codechef etc) from the route, and uses Puppeteer to scrap the appropriate user profile. Then the display name and rating of that user is pulled from the fetched page using an appropriate HTML selector, and this data is returned as JSON response.