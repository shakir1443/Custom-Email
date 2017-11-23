# Custom-SMS
A php script to send custom email to the user

## Step 1 : Install Wamp Server in Windows
Download wamp server from here.

Wamp : http://www.wampserver.com/en/

## Step 2 : Keep sendemail folder inside wamp folder
This is a software that will work as a mail sender.

## Step 3 : Make changes in sendmail/sendmail.ini
Provide your email and password in the following field.

auth_username=your_email

auth_password=your_password

force_sender=your_email

## Step 4 : Make changes in php.ini
Locate mail function and provide server, port, your email and location of sendemail.exe.

[mail function]

smtp_server= smtp.gmail.com

smtp_port = 587

sendmail_from =your_email

sendmail_path ="C:\wamp64\sendmail\sendmail.exe -t"

## Step 5 : Change settings in email
In case of gmail, go to my account. In Sign-in & security tab, go to Apps with account access. Allow less secure apps to On mode.
