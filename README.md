# vaultwarden
Vaultwarden docker-compose

.env Description

SMTP_HOST
This is your SMTP mailserver

SMTP_FROM
This is the email address messages will be sent from

SMTP_FROM_NAME
The name you wish to appear as the email account name on sent messages

SMTP_SECURITY
The security method used by your SMTP server. Possible values: starttls / force_tls / off

SMTP_PORT
This is the SMTP port used by your mail server. Possible values: 587 / 465

SMTP_USERNAME
This is the login for your SMTP mail server

SMTP_PASSWORD
This is the password for your SMTP credentials

SMTP_AUTH_MECHANISM
This is the SMTP authentication mechanism of your mail server. Possible values: Plain / Login / Xoauth2

Custom .env please check this configuraation https://github.com/dani-garcia/vaultwarden/blob/main/.env.template
