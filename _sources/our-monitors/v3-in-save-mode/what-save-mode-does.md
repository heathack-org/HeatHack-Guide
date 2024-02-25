# What save mode does

The monitor will take temperature and relative humidity readings every five minutes and save them.  It can store around a month's worth of readings.  Every time you restart the monitor, it will offer to download the data it has saved and start collecting data again.  There is no way to restart the device without downloading the data, but if you don't want the data file, you can delete it. 


```{admonition} Keep it running
:class: important

Don't turn the monitor off until you are ready to download the data. If you need to, you can always take the monitor somewhere else **still running** until you can deal with it.

The monitor is so cheap it relies on your phone or laptop to know what time it is when you start the device and when you pick up the data.  Its own internal clock can run fast or slow so we rely on these timings to correct the times in the data.  In a very cold venue, the clock could be slow by perhaps 20 minutes a week.  If anyone turns the monitor off and on without downloading the data, we can't make this correction.  

```

```{admonition} For spreadsheet lovers
:class: tip

If you want to handle the data yourself, the data is in a CSV (comma-separated values) that you can open in a spreasheet.  Each data line has a date-time, a temperature in degrees C, and a relative humidity in %RH.  If either reads 120, then there is a sensor fault.

Date-times are for Greenwich Mean Time.  These are the same as local time in the UK during the winter. During British summer time, local time is one hour later than GMT.  That is, if the timecode says 2024-04-20T13:00:00Z, that means 20 April 2024 at **2** p.m. local time.  If anyone turns the monitor off and on without downloading the data, then we don't know the start time.  The date-time is then given as an integer that counts up in elapsed minutes from 0.

The file has two header rows where the first is a key for the data in the second. "Location" in the string entered when the monitor was set up. "File date" is when you downloaded the file.  Our clock speed correction assumes that the first reading in the file is the start time for the device and scales the times linearly to cover the timespan between the first reading and the file date.  If the date-times are elapsed minutes, then we assume the clock runs at the correct speed to at least get something out of the data.

```



