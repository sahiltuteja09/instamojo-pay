
Instamojo payment gateway integration with Codeigniter

Instamojo library version 1.1

Classes developed by Sahil from freeclues.com

Development instruction from https://github.com/Instamojo/instamojo-php/

Further documentation is available at https://docs.instamojo.com/v1.1/docs


Usage

1. unzip folder to desktop

2. Copy file to their suitable folders

3. Create "order" table in your db. 

3.1 add two required columns

a.  instamojo_payment_id 
b.  instamojo_payment_request_id


4. Edit instamojo_model.php and set your API key and Auth token  " can be obtained from https://test.instamojo.com/developers/ "

5. Provide user and product details in imjo.php controller

6. Call URL http://example.com/imjo/pay

OPTION TO BE SET IN Intamojo_model.php

1.   send_email (boolean ) :  if you want to sent payment link via EMAIL ( by default True )
2.   send_SMS (boolean ) :  if you want to sent payment link via SMS ( by default True )
2. allow_repeated_payments (boolean ) :if you want user can pay more than once by the link you send from Email or SMS.( by default False )







