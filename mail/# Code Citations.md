# Code Citations

## License: unknown
https://github.com/tanya-ivanova/SoftUni-JS-Web-Development/tree/774c7c02b1b4fa7451f3183f0e91dee36a456136/ReactJS/1-Intro/website-react-demo/public/mail/contact.php

```
php
if(empty($_POST['name']) || empty($_POST['subject']) || empty($_POST['message']) || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
  http_response_code
```


## License: unknown
https://github.com/padlaab/padlaab.github.io/tree/432af530d4823a401762916e06c66173b1220a0f/mail/contact.php

```
']) || empty($_POST['subject']) || empty($_POST['message']) || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
  http_response_code(500);
  exit();
}

$
```


## License: unknown
https://github.com/fansize/fansize.github.io/tree/864a44729b8977f7e7a439d99e04c588bb234622/itranslate/mail/contact_me.php

```
$_POST['message']) || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
  http_response_code(500);
  exit();
}

$name = strip_tags(htmlspecialchars($_POST['name']));
$email =
```


## License: unknown
https://github.com/orestiskosko/delivernet/tree/7af66c59694e0fc1928287a6d3cc47bdaa619b11/DeliverNET/DeliverNET/Content/mail/contact_me.php

```
]) || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
  http_response_code(500);
  exit();
}

$name = strip_tags(htmlspecialchars($_POST['name']));
$email = strip_tags(htmlspecialchars($_POST
```


## License: unknown
https://github.com/astroraditya/portfolio-old/tree/5d133944ae4aff1f7a39586e5b610c44e2fa64f5/mail/contact.php

```
/ Change this email to your //
$subject = "$m_subject:  $name";
$body = "You have received a new message from your website contact form.\n\n"."Here are the details:\n\nName: $name\
```

