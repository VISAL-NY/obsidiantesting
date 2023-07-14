Acquiring Bank / Issuing Bank able to verify bill before submit payment or verify transaction after payment.


><font color="green"> <b>POST:</b></font> https://bankapi-demo.bill24.net/qr/verify

<h3>Header</h3>

>Accept : application/json
>Content-type : application/json
>Token : {<a href="">token</a>}


<h3>Request Parameter</h3>

><font color="orange"><b>khqr_string</b></font> (optional) <font color="red">String[255]</font>
>Raw string data of KHQR code (This parameter is use to verify bill)
><hr>
><font color="orange"><b>khqr_string</b></font> (optional) <font color="red">String[255]</font>
>Raw string data of KHQR code (This parameter is use to verify bill)
><hr>


<h3>Example Request</h3>

```JSON
{
    "khqr_string":"000201010212303400zmkbkhppxxx@amkb01032340203AMK520449005802KH5916សហ#$សស%ហ&eថ ក6010Phnom Penh540820400.0053031165502025603400622305092340005450706Bill2463044C97",
    "ref_no": "sdsad"
}

```


```php
<?php

$curl = curl_init();

curl_setopt_array($curl, array(
  CURLOPT_URL => 'https://bankapi-demo.bill24.net/qr/v2/confirm',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'POST',
  CURLOPT_POSTFIELDS =>'{
"khqr_string":"000201010212303400zmkbkhppxxx@amkb01032340203AMK520449005802KH5916សហ#$សស%ហ&eថ ក6010Phnom Penh540820400.0053031165502025603400622305092340005450706Bill2463044C97",
    "ref_no": ""
}',
  CURLOPT_HTTPHEADER => array(
    'Content-Type: application/json',
    'Accept: application/json',
    'token: a9310ee579c748cbaefb476b9b2180fb'
  ),
));

$response = curl_exec($curl);

curl_close($curl);
echo $response;
```


<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form> 

<form action="/action_page.php" id="form1">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <input type="submit" value="Submit">
</form>

<p>The "Last name" field below is outside the form element, but still part of the form.</p>

<label for="lname">Last name:</label>
<input type="text" id="lname" name="lname" form="form1">


```button
<a href="">rr</a>
```

<button >
<a href="http://www.google.com">click</a>
</button>
