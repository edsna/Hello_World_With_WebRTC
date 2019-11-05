"Hello World" web Application using webRTC

This is a sample "Hello World" Web Application that uses the getUserMedia() method to to request permission from a user to use their camera,
and streams the content captured by the camera through the browser when permission is granted.

This sample code is mobile friendly, meaning that it can run on mobile devices with browsers that support webRTC.

Please, remember that in order to run this sample code and have your camera accessible, you need to have it on your (local) web server. Clicking on the html link will only load the layout of the page. Why? because the browser will block the getUserMedia API if you don't serve it from a local web server. Even in the case of a web server, you need to 'allow' this permission when prompted because this option is desabled by default.

Regards,
Edson Zandamela"Hello_World_With_WebRTC" 
