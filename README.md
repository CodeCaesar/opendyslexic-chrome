# Open Dyslexic Chrome App

This is the source code for the chrome extension that's in the app store. Feel free to suggest changes and improvements. :)



##About 
OpenDyslexic is a new open source font created to increase readability for readers with dyslexia. The typeface includes regular, bold, italic, and bold-italic styles. It is being updated continually and improved based on input from dyslexic users. OpenDyslexic is free for Commercial and Personal use.

#Info
Number of Users : 22,000

Version Number : 3.0 

Download from the [chrome store](https://chrome.google.com/webstore/detail/opendyslexic/cdnapgfjopgaggbmfgbiinmmbdcglnam?hl=en)


##Set up

**Prerequisites:** [Node](http://nodejs.org/) and the following global node modules:  gulp (if you have none of these modules, just run npm run global-deps).
- Clone this repo locally ``` git clone  https://github.com/antijingoist/opendyslexic-chrome```
- Open up either terimal or CMD
- Naviagte to the repo 
- Run the following command inside the repo ```npm install```
- Then run ```gulp build```, which build all javascript and css.



##Install 
- See set up first 
- Open up Google chrome
- Go the Google Chrome Settings
- Go to extensions
- Click enable developer mode.
- Load unpackaged extensions.
- Pick the opendyslexic-chrome folder.


##Build Files
- Open up command line or termial
- Naviagate to the opendyslexic-chrome folder
- Run ```npm install ```
- Then ``` gulp build ```
- This will create a folder called dist and compress all css, and javascript :)
