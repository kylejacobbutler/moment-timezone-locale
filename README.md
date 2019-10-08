# moment-timezone-locale

ES6 Module of [momentjs](https://github.com/moment/moment) with locales and timezone bundled.


## Installation

Previously installed moment packages need to be uninstalled.

```
npm i @kylejacobbutler/moment-timezone-locale
```
```
jspm i npm: @kylejacobbutler/moment-timezone-locale
```

## Usage

```javascript
import moment from 'moment-timezone-locale';


Standard Usage:
moment(2014-06-27).fromNow()

Locale:
moment(20120627).locale('de').fromNow()

Timezone:
moment(20120627T12:00:00Z).tz("America/Los_Angeles").format('ha z')

```
