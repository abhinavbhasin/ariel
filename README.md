# ariel
Avatar Robot for Imaging and Electronic Liaison

##Dependencies

### [socket.io](http://socket.io)
Handles real time communication between the client and robot, or client <-> cloud server <-> robot

### [talky.io](https://talky.io)
RTC helpers to for peer to peer video and chat

### [hapi.js](http://hapijs.com/)
Server framework. Currently we are just using it for [routing](http://hapijs.com/tutorials/routing) http requests

### [johnny-five](http://johnny-five.io/)
The Javascript-Robotics programming framework

### [keypress.js](http://dmauro.github.io/Keypress/)
Handles keypress events on the client

### [virtualjoystick.js](https://github.com/jeromeetienne/virtualjoystick.js)
Virtual joystick for user page

##Learning Resources

###Fundamentals

* [nodeschool.io](http://nodeschool.io/#workshopper-list) is a pretty amazing (and fun!) way to learn about many of these topics. These are "choose-your-own-adventure" style workshops that let you build and check solutions to common problems.
* [JavaScript for Cats](http://jsforcats.com/) is a fun introduction to programming with JavaScript as a first language.

###Tips for the client side code

We're going to need to [Select Elements on the web page](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById) and then [add event listeners to those elements](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
