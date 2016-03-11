## Things we can track
+ Browser info (browser, device, operating system, + some other less important)
+ Referrer
+ Beacon clicks
+ Geolocation (via [http://freegeoip.net/json/](http://freegeoip.net/json/))
+ Bounce rate (total clicks / signups)
+ Email sign ups by day/month
+ Username reservations per day/month 
+ Dropoffs
  * Visitors vs clicks
  * Clicks vs emails
  * Emails vs usernames

---
######Stephen's notes
Use sendbeacon onunload + [this polyfill](https://github.com/miguelmota/Navigator.sendBeacon/blob/master/sendbeacon.js) for shitty browsers to async send data and cut down on requests