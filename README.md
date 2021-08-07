# ZXHN-H108N-Router-Unauthenticated-Telnet-Utilities
A few utilities to use by exploiting the unauthenticated Telnet vulnerability. All the utilities could be used on machnes connected to the router without admin access.

**Restart Router**

As basic as it is, it simply restarts the router. You simply run the following command:

`./restartrouter`


**Change Wifi Password**

Change the wifi password by running the following command:

`./chgWifiPasswd your_pasword`


**Automatic Password Changer**

  This is a simple script that uses the Wifi password changer to assign a random wifi password then emails it. Could be simply put in a cron job to be run daily. You could simply run it like this:
  
`./passwdChanger your_email`
  
