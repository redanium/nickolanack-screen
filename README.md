# nickolanack-screen
Experiment making a remote desktop control over websockets using node, robotjs, and electron


This is a proof of concept project - a remote desktop viewer using nodejs, and robotjs. the desktop screen server broadcasts screen updates as bitmap tiles to a client, which displays the tiles on an html canvas. the client is created with electron, but could be a simple html+javascript page.

![alt tag](https://raw.githubusercontent.com/nickolanack/nickolanack-screen/master/ScreenShot2016-10-12.png)

of course this is not very fast or efficient at the moment, but I intend to experiment with compression and optimization
