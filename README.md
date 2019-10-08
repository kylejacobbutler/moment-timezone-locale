# moment-timezone-locale

ES6 Module of [momentjs](https://github.com/moment/moment) with locales and timezone bundled.


## Installation

Previously installed moment packages need to be uninstalled.

```
npm remove moment moment-timezone
npm i @kylejacobbutler/moment-timezone-locale
```
```
jspm i npm: @kylejacobbutler/moment-timezone-locale
```

## Usage

```javascript
import moment from 'moment-timezone-locale';
or
import moment from '@kylejacobbutler/moment-timezone-locale';
```

## Moment:

```javascript
moment(2014-06-27).fromNow();
```

## Locale:

```javascript
moment(20120627).locale('de').fromNow();
```

## Timezone:

```javascript
moment(20120627T12:00:00Z).tz("America/Los_Angeles").format('ha z');
```


