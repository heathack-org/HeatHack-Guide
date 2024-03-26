# Check for data

You can now go back on the internet to check whether your monitor connected properly.  Go to wifi settings, connect to your venue's wifi, and visit the thingspeak address written on the outside of your monitor.

::::{grid} 1 1 1 2 
:gutter: 2

:::{grid-item-card}  Where to find the ThingSpeak address
```{image} /images/monitoring/v3/thingspeak-url-label.jpg
:alt: 
:class: mb-1
:height: 400px
:align: center
```
:::

:::{grid-item-card} What you will see on Thingspeak

```{image} /images/monitoring/thingspeak-last-temp.png
:alt: 
:class: mb-1
:width: 400px
:align: center
```
:::
::::

Your ThingSpeak page might look a bit different as we have to set up each one by hand and don't always remember.

The page has read-out of the most recent temperature received along with how long ago ThingSpeak received it.  If you have only just turned the monitor off and on, this should be recent.  The website usually shows the reading within a minute or two.  


If everything looked like it worked but you don't see any data on ThingSpeak within 5 minutes, you probably entered the wrong password and will need to try again.  

To help you tell what's happening, the monitor flashes once when you first turn it on and each time you turn it on, flashes 10 times the first time it sends data to the internet successfully.  This can take a minute after you press "Submit", or, if you have turned the monitor off and on, two or three minutes.

<!-- TODO -->
<!-- The light on the monitor will also flash 10 times if it manages to get readings to the internet, but this can take up to minute -->
<!-- Seeking clarification of whether it happens only on submit pressing or on power cycle -->
