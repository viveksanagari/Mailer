# Mailer

An email functionality for a HTML form using PHP.

Limitation:
The "Less secure app access" feature needs to be turned ON from the "Security" section of your Google account (SENDER's ACCOUNT), to make this work. 

- Go to https://myaccount.google.com/ to access your google account. 
- Click on the "Security" option to the left. 
- Scroll down to find the "Less secure app access" and turn it ON.

The less secure app access needs to be turned ON in order to allow the gmail account to send the email. If not the gmail account considers that the account has been accessed by a non secure application and blocks the email.


Before starting to use this code,

Mandatorily fill the sender email address in email.phtml:
      $mail->Username = '';

Mandatorily fill the sender email password in email.phtml:
      $mail->Password = '';

Mandatorily fill the company receiver email address in email.phtml:
      $mail->AddAddress('');

