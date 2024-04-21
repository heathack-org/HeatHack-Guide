(data-logging)=
# Temperature and relative humidity readings


Regular temperature readings are very useful for understanding where you are wasting energy on heating.  Monitoring often indicates that a small change in practice or a small investment in different heating controls will save enough money to be worth the bother.  In buildings that are slow to warm up and not used all the time, it's common to discover a quarter of the heating is wasted, and we have sometimes found much bigger problems, like a church hall that had accidentally been heated 24/7 for years.  Monitoring will also help you understand and handle user complaints and know when maintenance is required.

Your heating controls might already log room temperature for you.

Relative humidity readings are also useful if you have any concerns about damp or dryness in your building.  That might be because you want to be sure the conditions are right for people, or it might be because you want to safeguard the building or its contents.  This is less important than recording temperature because if it's too damp or too dry for the people in the building, it should be obvious.  However, if you are a church with a pipe organ or other sensitive furnishings, or a building with unfrequented spaces that you think might be damp, it's useful to have a device capable of monitoring relative humidity (RH) so you can use it for this some of the time.  It's difficult to measure relative humidity accurately so you should treat the readings as approximate.

::::{grid} 1 1 1 2 
:gutter: 2

:::{grid-item-card}  Home-built thermal monitor 
```{image} /images/monitoring/bare-monitor.jpg
:alt: 
:class: mb-1
:height: 200px
:align: center
```
:::

:::{grid-item-card} Commercial logger
```{image} /images/commercial-logger.jpg 
:alt: 
:class: mb-1
:height: 200px
:align: center
```
:::
::::

If you have the money, you can get a commercial "data logger".  These are usually USB sticks and are easy to use with free software provided.  The cheaper options don't send data to the internet.  Instead, you have to pick up the data using the software on a computer.   There are several companies that make them.  It costs around £45 to get a commercial temperature logger, £65 to get one that logs temperature and relative humidity, and £140 to get one that sends data to the internet for cloud storage.    
Devices from less established companies might be cheaper, but it's possible you get what you pay for - we aren't sure.  Lascar Easylog USB is a common choice so you could compare your options to those.


- [Lascar EasyLog USB - basic temperature model](https://www.lascarelectronics.com/easylog-el-usb-1)  
- [Lascar Easylog USB - basic temperature plus RH model](https://www.lascarelectronics.com/easylog-el-usb-2)
- [Lascar Easylog USB - temperature plus RH with an internet connection and cloud data storage](https://lascarelectronics.com/data-loggers/temperature-humidity/el-wifi-th/)

We have volunteers who use cheap electronic parts to make something that can be used either to save the data to pick up or send it to the internet for cloud storage.  They aren't as good as a commercial data logger, especially if you don't have wifi in your building, because they are buggier and harder to use.  If you have wifi, any pain is just at the beginning to get them connected - after that, they usually just work.  Some have been running for over a year but a few groups haven't managed them at all and quite a few have needed phone help from us while they are setting it up.  We're still discovering improvements we can make.  If you'd like to try one, let us know.  They are currently free but in future we may suggest you make a donation to cover the cost of parts and postage. 

- [How to Use Our Thermal Monitors](our-monitors)

We just use the word "thermal monitor" to mean either what our volunteers build or a commercial data logger because people find the term less puzzling.


```{admonition} A new option we are testing

We are evaluating the Thermopro TP357s as an alternative to our own devices.  We think it could be especially useful for venues without wifi.  It has a battery-operated sensor unit with a phone app to retrieve the data over a Bluetooth connection.  It's intended to be used for live monitoring of, say, a nursery at home, but it stores some data on the sensor unit itself to cover when the phone is out of range.  

If you try this, be careful to get the new model (since February 2024), the 357s.  The manufacturer tells us the following web link has the right one even though it says "357".  Note that the page does mention the export feature.  

- [Thermopro TP357s, labelled as TP357, but correct product at 17 April 2024](https://www.amazon.co.uk/dp/B093PT1NL1?ref=myi_title_dp&th=1)

Earlier models won't let you download the data by emailing it to someone.  They also appear to have a web store on Ali Express and the chat advisor we talked to on their official website was helpful, if you prefer them to Amazon.

A phone can work with more than one Thermopro at a time as long as they are all in range. We don't know what the actual range and battery life will be in practice either, and there are some reports of data loss when the battery dies.   This means you could retrieve the data when you visit the venue, but it might be safer to leave an old phone with Bluetooth on plugged in within perhaps 10m of the sensor unit.  A good hiding place is attached to the back of an internet router using a USB port to keep it charged.  The app itself should work with any Android or Apple phone bought since around 2016, but we're less sure about whether the version of Bluetooth on any phone will always be compatible with the one on the sensor unit.  If you try an old phone, it doesn't need security updates, but do ensure the phone can't be used to access any of your personal information or finances, for instance, by making sure it's protected with a secure PIN or biometrics, or deleting apps and registering it to a new email address.  You can turn wifi off.  Take the SIM out in case you've made it possible to reset any of your accounts from its phone number.

For long term use, you'll want a way to "downsample" downloaded data so that it isn't a reading every minute, to save storage space.  If the community starts using these we'll think about how to set up an automated service for this.
 
```