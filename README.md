# Yam'in
#### Chrome plugin for Yammer

Yam'in was built to increase employee engagement on Yammer by integrating the Yammer experience to the browser in the form of a plugin so they don't have to switch tabs to stay connected to the Enterprise network.

### Features
- Threaded view of conversations
	+ interact with posts with like/unlike, reply and share inline to the thread
	+ look at the current no.of likes, shares and replies to a thread
- All/Top/Following classification as in the web interface for the network feed
- Personal notifications
- Mentions and messages
- Users listing, search and profile view
- Groups listing and message threads within a group
- Enterprise Network Analytics
- Recent Activity within the Enterprise Network
- Search message threads and people 

### Developer notes

### How do I install this?

Its published to chrome web store, checkout and install plugin from here [https://goo.gl/qJ5KsX]

Also you can install in developer mode, follow the steps below.

+ Clone or download zip from [https://github.com/Imaginea/yam-in](https://github.com/Imaginea/yam-in)
+ Install gulp and all dev dependencies (you can find them in package.json). 
+ Run the command `gulp build:src` and `gulp build:templates` in the <cloned> directory.
+ Open Chrome *Settings* page, click on *Extensions*
+ Check *Developer mode* check box.
+ Click on *Load unpacked extension* and navigate to the \<cloned\>/build folder.

Now your yammer feed plugin is installed.

### How do I use it?

+ Click on the plugin button and authorize the application to access your yammer feed.
+ A browser window is opened which will prompt you to authorize the app, click on *Allow* button, this will close the browser window.
+ Click on yammer feed plugin now to see your feed.

### License
The project is available under MIT License. Find the full license text [here](./LICENSE.md)

### Contributors 
*Listed in alphabetical order*

- Kiran D
- Krishnam G 
- Manoj P
- Mohan T
- Prabin B
- Risav V
