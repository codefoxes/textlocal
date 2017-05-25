## Textlocal

This is Textlocal composer package.

## Install
`composer require codefoxes/textlocal`

## Usage
```
require_once 'vendor/autoload.php';

use CodeFoxes\Textlocal\Textlocal;

$smsAagent = new Textlocal( 'you@site.com', `01234yourhash56789` );

$smsAagent->sendSms( array('919876543210'), 'My message.', 'APROVD');

```

