# disable-ssl-certificate-validation-in-java
Using HTTPS to connect to an other server

- Call **SSLTool.disableCertificateValidation()** funtion to use the functionality before connecting to other server
- It is **not advised** to disable certificate validation unless it is only for testing purposes.
- If you are using **HttpsURLConnection**, you can use this code
- for example you can look at this link: https://stackoverflow.com/questions/54516557/disable-ssl-certificate-validation-in-java
