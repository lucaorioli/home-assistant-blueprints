# home-assistant-blueprints
Blueprints to manage a fan to de-umidify a room.
It works in perc of umidity. I think better using thermal comfort and use "Absolute Umidity" sensor instead of normal umidity.
When you turn off manually the fan the signal is lost and the blueprint turn on the fan only if umidity goes down and then up the given perc.
If you turn manually on the fan it is automatically turned of after given minutes.
