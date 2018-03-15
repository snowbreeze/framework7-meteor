#Framework7 + Meteor
Simple integration of Framework7 v2 on Meteor

## Getting Started

Clone the repo 

```
git clone https://github.com/snowbreeze/framework7-meteor
```

Cd into the framework7-meteor folder and Run meteor

```
cd framework7-meteor
meteor
```

## DIY

You can do this on your own project without needing to clone this repo as well. Here is how

* Goto (https://github.com/framework7io/framework7) and download the files
* Copy the dist/css/framework7.css and dist/js/framework7.js file
* Create a folder inside your project's client folder and name it compatibility
* Paste the files there
* On any of your css files inside client, add this line. This is done because somehow meteor makes the view's height 0.
```
#app {
    height : 100vh;
}
```
* You are good to go! To understand how to scaffold the html and initialize the js, you can check out my example.

#Cheers! :beers:
