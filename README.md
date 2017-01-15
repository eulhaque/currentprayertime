# currentprayertime
Magic Mirror Module to display the current islamic prayer time and also play Adhan

#config 
To add the module do the following which also shows the configurable values:

````javascript
{
    module: 'MMM-Advent',
    position: 'bottom_center', // This can be any of the regions, best results in center regions
    config: {
        updateInterval: 10 * 60 * 1000, // every 10 mins
		    latitude:41.092739,  //defaults to Norwalk, CT, US
		    longitude: -73.419796,
		    timeZoneString: "America/New_York",
		    method: 2, //https://aladhan.com/prayer-times-api
		    school: 1, //"school" - Optional. 0 for Shafii, 1 for Hanfi. If you leave this empty, it defaults to Shafii.
		    adhanSrc: 'http://www.islamcan.com/audio/adhan/azan1.mp3',
		    css_class: 'bright medium',
    }
},
````
