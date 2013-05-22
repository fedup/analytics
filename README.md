
# analytics

  Simple wrapper around Google Analytics

## Installation

    $ component install fedup/analytics

## API

    var analytics = require('analytics');

    analytics.trackEvent({
        category: "foo",
        label: "bar",
        value: "baz"
    });

    analytics.push('_trackPageView', [data]);

## License

  MIT
