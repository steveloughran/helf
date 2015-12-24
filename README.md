# helf
spark against msft health checking

## Links

* [Microsoft Health Dashboard](https://dashboard.microsofthealth.com/)
* [Main API doc](https://developer.microsoftband.com/cloudAPI)
* [Microsoft Health Cloud API V1](https://developer.microsoftband.com/cloudAPI/Explorer)



## Privacy Policy

This code runs locally and executes GET calls against the Microsoft Health API
Servers only. This application does have access to that data, but it is only
retained on your system/any spark cluster you are working with.

If you are using this code against a Hadoop cluster, it is your responsibility
to secure it. We recommend Kerberos authentication and wire encryption.
