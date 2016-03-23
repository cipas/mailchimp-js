# mailchimp-js

Node.js client of [MailChimp API 3.0](http://developer.mailchimp.com/documentation/mailchimp/reference/overview/).

## Usage

```javascript
var Mailchimp = require('mailchimp-js');
var mailchimp = new Mailchimp('YOUR_API_KEY');

mailchimp.campaigns.create();
```

## Changelog

See changelogs in [CHANGELOG](CHANGELOG.md)

## Author

Marvin Lam <lam@seedalpha.net>

## License

[Copyright © 2016 SeedAlpha, All rights reserved.](LICENSE.md)