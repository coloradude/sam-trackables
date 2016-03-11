## Things we can track
+ Browser info 
  * Browser 
  * Device 
  * Operating system
  * + some other less important
+ Referrer
+ Geolocation (via [http://freegeoip.net/json/](http://freegeoip.net/json/))
+ Email sign ups by day/month
+ Username reservations per day/month 
+ Dropoffs
  * Visitors vs clicks
  * Clicks vs emails
  * Emails vs usernames

---
######Stephen's notes
Use sendbeacon onunload + [this polyfill](https://github.com/miguelmota/Navigator.sendBeacon/blob/master/sendbeacon.js) for shitty browsers to async send data and cut down on requests