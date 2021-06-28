# disable-ssl-certificate-validation-in-java
Using HTTPS to connect to an other server

- Call **SSLTool.disableCertificateValidation()** function to use the functionality before connecting to other server
- It is **not advised** to disable certificate validation unless it is only for testing purposes
- The SSL, and TLS can be disabled also in **jdk**. Open **java.security** file from the path: *installedjdk/jdkVersion/jre/lib/security/*. Find the **jdk.tls.disabledAlgorithms** property. You can add **jdk.tls.disabledAlgorithms**=SSLv3, TLSv1, TLSv1.1 or remove them. But it is **not advised** to put SSLv3 or TLS in disabled mode unless it is only for testing purposes
- If you are using **HttpsURLConnection**, you can use this code
- for example you can look at this link: https://stackoverflow.com/questions/54516557/disable-ssl-certificate-validation-in-java
