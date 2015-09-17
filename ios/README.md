# iOS client

This iOS client can be downloaded from the [Apple App Store](https://itunes.apple.com/us/app/physical-web/id927653608?mt=8). A walkthrough of the app [is here](http://github.com/google/physical-web/blob/master/documentation/android_client_walkthrough.md) (Android version) and will show you how to put your URL into a beacon.

Keep in mind that this software is just a prototype and this project is originally concept to be published on AppStore. If you want to run in your machine for learn purposes you're going to have to fix some dependencies. 

To fix the iOS dependencies or you can clone Jeff Prestes' fork ([https://github.com/jeffprestes/physical-web](https://github.com/jeffprestes/physical-web)) or after clone the original project follow these steps:

* Open the Terminal and access the project location
* And executes: ```git pull --rebase --prune && git submodule update --init --recursive```
* Open the project on XCode 
* Delete the dependencies references that are missing
* Add the dependencies files from third-party folder. 
* Delete Today's task (it's works only for the project team that upload the offical Physical App to AppStore)
* Fix small import references
* Clean and build the project


