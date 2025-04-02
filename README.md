## General Proxy for front end and backend applications

This app is important to automatically generate ssl certifications for applications running in contaniers

Use the same network for the applications that will get the certifications and domains.

Here is the proxy and the https certifiication, no need to restart this containers because it detects if an application is correctly configured, it will detect, generate certificates and expose.

The `certs` contains all SSL certificates, and they update automatically.