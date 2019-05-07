# ![LOGO](logo.png) PageSpeed Insights **flow**ground Connector

## Description

A generated **flow**ground connector for the PageSpeed Insights API (version v5).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/pagespeedonline/v5/swagger.json<br/>
Generated at: 2019-05-07T17:41:49+03:00

## API Description

Analyzes the performance of a web page and provides tailored suggestions to make that page faster.

## Authorization

This API does not require authorization.

## Actions

### Runs PageSpeed analysis on the page at the specified URL, and returns PageSpeed scores, a list of suggestions to make that page faster, and other information.

*Tags:* `pagespeedapi`

#### Input Parameters
* `category` - _optional_ - A Lighthouse category to run; if none are given, only Performance category will be run
* `locale` - _optional_ - The locale used to localize formatted results
* `strategy` - _optional_ - The analysis strategy (desktop or mobile) to use, and desktop is the default
    Possible values: desktop, mobile.
* `url` - _required_ - The URL to fetch and analyze
* `utm_campaign` - _optional_ - Campaign name for analytics.
* `utm_source` - _optional_ - Campaign source for analytics.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-pagespeedonline-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
