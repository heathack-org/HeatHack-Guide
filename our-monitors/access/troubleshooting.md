(access-troubleshooting)=
# Troubleshooting access to the monitor

These tips are for if you can't manage to connect the monitor to set it up and apply for all monitor versions.

To get past your phone, laptop, or tablet assuming you're trying to use the internet:

- click "allow" or "connect anyway" on any pop-ups pointing out the lack of internet.
- Think about what wifi networks your phone knows how to join in the building, and turn off "re-connect automatically" for them until you've finished setting up the monitor.   If there's no option to do this you may need to "forget" the local wifi networks and re-add them when you are done.
- Unplug ethernet cables, USB cables providing wired internet, and USB wifi dongles
- Open a new tab in your browser to type 192.168.4.1 into the address bar - otherwise some browsers try to search the internet for it.

To get past the security settings temporarily:

- In your browser's security settings, allow insecure content.  This might mean you need to turn on "allow insecure content", turn off "always use secure connections", and/or turn off "always use HTTPS".  
- Disable anti-virus and anti-malware software.   For instance, in Norton 360 disable "Auto-Protect" and "Smart Firewall". 
- Turn off any security-related browser extensions.
- On Apple devices, in the security settings, change "network/device isolation" from True to False.  We think this is a new feature that ensures your device will only connect to the internet and not to other devices around you.



Here are some pictures of screens you may see indicating that your device considers the monitor incapable or insecure:


::::{grid} 1 1 2 2 
:::{grid-item-card}  Successful connection to heathack-s despite lack of internet 
```{image} /images/monitoring/troubleshoot-access/no-internet-secured.png
:alt: pop-up reading heathack-s no internet, secured
:class: mb-1
:width: 400px
:align: center
```
---
This is working - go ahead and go to 192.168.4.1 in a new tab.

:::

:::{grid-item-card} Insecure connection warning 
```{image} /images/monitoring/troubleshoot-access/insecure-connection-warning.png
:alt: pop-up that starts 192.168.4.1:1 Your connection to this site is not secure 
:class: mb-1
:width: 400px
:align: center
```
---
You may need to go to site settings - an option at the bottom - and use the "privacy and security" settings to allow insecure content.
:::

::::