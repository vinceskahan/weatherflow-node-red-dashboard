This is a quick node-red dashboard for the WeatherFlow station.

It listens to the UDP messages broadcast on port 50222 from the
station, seeds MQTT topics (to a hostname 'mqtt') for each type
of measurement, and seeds a rudimentary dashboard.

This is a demo of course, and your mileage may vary.  Salt to taste.

I have debug nodes that are by default 'off' if you want to just
see what the app is receiving from the UDP broadcasts.



