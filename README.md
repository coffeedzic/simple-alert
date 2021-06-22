# Simple Alert
Simple JavaScript Alerts

![Simple Alert Preview](https://apps.coffeedzic.com/simple-alert/preview.jpg)

## Test it live

[apps.coffeedzic.com/simple-alert](https://apps.coffeedzic.com/simple-alert)

## Basic usage

![Alerts Preview](https://apps.coffeedzic.com/simple-alert/alerts.jpg)

#### Include JS & CSS file

``` html
<link rel="stylesheet" href="simple-alert.min.css">
<script src="simple-alert.min.js">
```

#### Call it easily in your application

``` js
simpleAlert.success('Your success text goes here');
```

## Success, Error, Info, Warning

You can call 4 different alerts

``` js
simpleAlert.success('Success');
simpleAlert.error('error');
simpleAlert.info('info');
simpleAlert.warning('warning');
```

## Change parameters

You have option to change three parameters

1. Text message
2. Duration of alert
3. Animation

#### Text message

``` js
simpleAlert.success('Your text message goes here...');
```

#### Duration of alert

Example: Duration of 5000 milliseconds (5s)
Default duration is 3000 milliseconds (3s)

``` js
simpleAlert.success('Your text message goes here...', 5000);
```

#### Animation

Available animations: 'swing-in', 'bounce' & 'slide'
Default animation is 'swhing-in'

``` js
simpleAlert.success('Your text message goes here...', 5000, 'bounce');
```

## License

Shrink PHP is licensed under the [MIT](https://github.com/coffeedzic/simple-alert/blob/main/LICENSE) license.



