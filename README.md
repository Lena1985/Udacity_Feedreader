# Feedreader Testing


## How to run the App
-----------------------------

* If you open the app locally you can run it on a localhost. If you are not familiar with doing that, here are the insructions:

* You need to install Python. But if you are using Linux or Mac OS X, it should be available on your system already. If you are using Windows, you can get an installer from the Python homepage and follow the instructions to install it:

* Go to www.python.org
* Under the Download section, click the link for Python "3.xxx".
* At the bottom of the page, choose the Windows x86 executable installer and download it.
* When it has downloaded, run it.
* On the first installer page, make sure you check the "Add Python 3.xxx to PATH" checkbox.
* Click Install, then click Close when the installation has finished.
* Open your command prompt (Windows)/terminal (OS X/Linux). To check Python is installed, enter the following command:

* python -V

* This should return a version number. If this is OK, navigate to the directory that your example is inside, using the cd command.

# include the directory name to enter it, for example
* cd Desktop
# use two dots to jump up one directory level if you need to
* cd ..

Then enter the command to start up the server in this directory:

# On Mac and Linux
* python -m SimpleHTTPServer
# On Windows
* python -m http.server

Go back into your browser and type in the URL "localhost:8000"

Then you can use the App...


### OR

* open **index.html** in your favorite browser!


## Testing

In this project Jasmine is used to test a feedreader application. **The following tests are run:**

* Feeds
  * Feeds are defined
  * Feed has a URL
  * Feed has a name

* Menu
  * The menu is hidden by default
  * The menu changes visibility when the menu link is clicked
  
* Entries
  * There are entries in the feed
  
* New Feed
  * The feeds are updated when a new feed is selected
  
## Results

You can view the test results by scrolling to the bottom of the page. All 7 test should pass. This is indicated by the green dots and text description.