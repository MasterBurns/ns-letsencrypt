To be used with [Netscaler Certificate Automation](http://techdrabble.com/citrix/18-letsencrypt-san-certificate-with-citrix-netscaler-take-2) process.  Please checkout blog for how-to.

Uses [dehydrated](https://github.com/lukas2511/dehydrated) to create and renew certificates.  Then Python scripts utilizing REST API to update Netscaler.




Edit MasterBurns: for http-01 challenge    
If you get Error's that your Server is to slow check if youre firewall allows the acme Protokoll  
Also check if port 80 is open to your ADC
