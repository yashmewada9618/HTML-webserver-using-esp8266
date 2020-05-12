# HTML-webserver-using-esp8266
Basics of controlling any device or sensor reading with esp8266 using webserver

Here we will create a webserver using esp8266 as Access point and any device connecting to it will be our client.
This server and client works on HTTP protocol.

There are two operating modes of esp8266...
1. STA(station) - connecting to existing network.
2. Soft AP(Access point) - creating its own network.

Here is a basic example of how to use esp8266 for creating a basic html webpage.It also consists of 
basic HTML code written in "string sendhtml".
while the code written in string ptr is the code for webpage creation.

We wil be using esp8266 webserver library compatible with arduino and create an access point from it.

we will be creating 2 urls and 4 handles.
handle_on_connect
handle_ledon
handle_ledoff
handle_notfound.

