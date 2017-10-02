# Users documentation
This is the documentation for USERS

## This is a subtitle
Below is a code block

```php
$url = {your.server}/api/users/

$handle = curl_init($url);
curl_setopt($handle, CURLOPT_POST, true);
curl_setopt($handle, CURLOPT_POSTFIELDS, $data);
curl_exec($handle);
curl_close($handle)

```
