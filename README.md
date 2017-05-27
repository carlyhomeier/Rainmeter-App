# WeatherAppRainmeter
A simple Rainmeter weather app that displays the time, date, and weather in your configured area in your configured color over any open applications. Useful for multi-screen users.<br />
Instructions for new users:<br />
Download Rainmeter<br />
Download TimeDateWeatherMin_1.0.rmskin<br />
Right click Rainmeter icon in taskbar (right side, small icon)<br />
Click Manage<br />
Click the arrow to the left of TimeDateWeatherMin<br />
Click TimeDateWeatherMin.ini<br />
On the top right, click load. (If it says unload, do not touch it)<br />
You should see the app in the top left of your main screen<br />
Click and drag the app to where you want it (make sure to click a letter, not the background, or else it wont drag)<br />
Go back to the manage screen<br />
Click edit on the TimeDateWeatherMin.ini<br />
Under [WeatherSite], find URL=...<br />
Replace 00000 with your zipcode<br />
Under [MeterTime], [MeterTemp], [MeterDate], find FontColor<br />
Change 255,255,0 to any color you want in all three section (unless you want your app multicolored)<br />
-Note: 255,255,0 represents yellow in RGB, to find your custom color google RGB color picker<br />
That's it!<br />
![alt text](https://github.com/chomeier/WeatherAppRainmeter/blob/master/WeatherAppPicture.PNG)
