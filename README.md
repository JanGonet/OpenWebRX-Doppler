# OpenWebRX-Doppler

<img src="https://github.com/studentkra/OpenWebRX-Doppler/blob/main/Example.jpg" height="120"/></h1>

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ApUIqlX7GXU/0.jpg)](https://www.youtube.com/watch?v=ApUIqlX7GXU)


OpenWebRX satellite Doppler tracer

Based on 

https://github.com/shashwatak/satellite-js

How to use:

For admins:

Place two files sat.js and append.js to 
```/usr/lib/python3/dist-packages/htdocs/plugins/receiver/``` 
folder.

Replace your GPS in append.js file.

Open "Photo desctiption" and paste this text:


```<script src="static/plugins/receiver/sat.js"></script>```

```<script src="static/pludins/receiver/append.js"></script>```


You will see smal panel under the main panel in web interface of OpenWebRX.

Tune the real frequency of Satellite, enter Norad-ID and press "GO" button.

You will see the name of satellite and trackin is running.

If TLE of satellite will no be fined, you will see alert message.

For users: 

Just paste the content of two files in browser console (F12 button) and press enter.
