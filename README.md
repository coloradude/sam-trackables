## Things we can track
+ Browser info **pie graphs**
  * Browser 
  * Device 
  * Operating system
+ Referrer **pie graph**
+ Geolocation (via [http://freegeoip.net/json/](http://freegeoip.net/json/)) **table for now possible map later**
+ Action frequency by day/month **line graphs**
  * Beacon clicks
  * Email signups
  * Username reservations 
+ Dropoffs by day/month **line graphs**
  * Visitors vs clicks
  * Clicks vs emails
  * Emails vs usernames

---
######Stephen's notes
Use sendbeacon onunload + [this polyfill](https://github.com/miguelmota/Navigator.sendBeacon/blob/master/sendbeacon.js) for shitty browsers to async send data and cut down on requests