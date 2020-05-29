# Chrome-Logger

## A chrome extension that logs the current page's network requests, page interactions and cookies for debugging purposes.

### Contributing

#### UI and Design
refer to the chrome extension docs as far as sizing, rules, etc.

#### Background Scripts
The background script should be unopinionated as far as domain and site. We should be monitoring the active tab only. Please use the chrome APIs as they provide most of the needed functionality. Timestamps are imperative for every log so as to construct a timeline of events.

#### Output
Be sure to make everything nice and organized no matter form of output integrated. Generally, txt, and JSON files should do just fine. Remember that it should be displayed as a timeline of events!