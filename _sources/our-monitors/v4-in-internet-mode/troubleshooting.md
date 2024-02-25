# If it won't connect

Some devices, especially Apple ones, aren't happy that our monitors are too simple to have modern security protections.  To get past the security settings temporarily:

- In your browser's security settings, allow insecure content.  This might mean you need to turn on "allow insecure content", turn off "always use secure connections", and/or turn off "always use HTTPS".  
- Disable anti-virus and anti-malware software.   For instance, in Norton 360 disable "Auto-Protect" and "Smart Firewall". 
- Turn off any security-related browser extensions.
- On Apple devices, in the security settings, change "network/device isolation" from True to False.  We think this is a new feature that ensures your device will only connect to the internet and not to other devices around you.

Don't forget to change the settings back again afterwards.


::::{grid} 1 1 2 2 
:::{grid-item-card}  Successful connection to heathack-s despite lack of internet 
```{image} /images/monitoring/troubleshoot-access/no-internet-secured.png
:alt: pop-up reading heathack-s no internet, secured
:class: mb-1
:width: 400px
:align: center
```
---
This is working.

:::

:::{grid-item-card} Insecure connection warning 
```{image} /images/monitoring/troubleshoot-access/insecure-connection-warning.png
:alt: pop-up that starts 192.168.4.1 Your connection to this site is not secure 
:class: mb-1
:width: 400px
:align: center
```
---
You may need to go to site settings - an option at the bottom - and use the "privacy and security" settings to allow insecure content.
:::

::::