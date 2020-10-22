# eskiz-sms-client

## Installing

`composer require napaeduhub/eskiz-sms-client`

then

`php artisan vendor:publish --provider=Napa\R19\SmsServiceProvider`

## Using

`Sms::send('998901234567', 'Sms from PHP/Laravel application');`
