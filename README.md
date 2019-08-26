# Visa Scanner
![Preview](https://github.com/ilmoislamnsu/SU19CSE299S02G01NSU/blob/master/Project%20Code/Assets/app-icon/ios-marketing.png)

#### A minimal visa scanner application built that will scan the visa and translate the language in English to help users.

Download the APK : [Installable APK](https://github.com/shoumma/Mister-Poster/raw/master/apk-releases/mister-poster.apk)

![Preview](./visual_designs/show.png)

## Built With
 - [Swift 4](https://swift.org/blog/swift-4-0-released/)
 - [Objective C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
 - [Firebase](https://firebase.google.com/)

### Documentations

## Walkthrough
### Sign In / Sign Up View

![Preview](./visual_designs/signIn.gif)

The Sign-In/Sign-Up view is pretty straight forward. Component's own states are maintained to display forms. We have use swift-4 via Xcode for designing. 


### Home View

![Preview](./visual_designs/post.gif)

After a successful sign in or sign up, the user will be directed to the Home view. These view are created using the Xcode(https://developer.apple.com/xcode/) maintained by Swift state. Based on user's sign-in status, the user will be displayed the Home View or the Sign In / Sign Up View.

The Home View is consists of four tabs -

 - The Universal Timeline
 - Create New Post
 - Own Posts
 - Settings

These are swipeable tabs that are created by using the library [react-native-scrollable-tab-view](https://github.com/skv-headless/react-native-scrollable-tab-view). The top navigation bar is a customized one which I hacked from one of the examples of the library.

The "Universal Timeline" component is a scroll view with "pull to refresh" functionality by using the [refresh control](https://facebook.github.io/react-native/docs/refreshcontrol.html). All the data are coming from Firebase NoSQL database. The next "Create New Post" component is used for creating a new post to the timeline. "Own Posts" will display own post count and own posts. Long press on any post from "Own Post" component will alert the user about deleting that post. Lastly, the "Settings" component is used to Sign Out the user or Delete account.


## How to create your own copy of this app?
### Prerequisites
To create an own copy of this application, you have some prerequisites. They are -

 - At first you need an Apple Machine like [macos mojave](https://cleanmymac.macpaw.com/19?campaign=cmmx_search_mojave_lowcpc_en&ci=804997884&adgroupid=59549465256&adpos=1t1&ck=macos%20mojave&targetid=kwd-520276011510&match=p&gnetwork=g&creative=338314487886&placement=&placecat=&accname=cmm&gclid=CjwKCAjw44jrBRAHEiwAZ9igKInZNZVQdjpTSIcqlKnd0LC5kFSyFDtI40RVtKEEjr2YPcRP7_pj2RoCUwEQAvD_BwE).
 - [Xcode](https://developer.apple.com/xcode/) installed on your system.
 - [Swift-4](https://swift.org/blog/swift-4-0-released/) installed on your system. 
 - [Git Desktop](https://desktop.github.com) installed on your system and a Git(https://github.com) account.
 - A google account for having [Firebase Web](https://firebase.google.com/docs/web/setup) configuration.

### Make own copy
First clone the repository using:

    git clone https://github.com/ilmoislamnsu/SU19CSE299S02G01NSU

Then install the necessary dependencies.

At this point you need to have the configurations for a Firebase App. Just go to [Firebase Console](https://firebase.google.com/docs/web/setup) and follow the instructions.
Then run the Xcode server.

Open your emulator and wait until it completely boot up. Then run the following command to run the app on the emulator.

Now, you have your own copy of this application!

## Path for Future Work
* Add search functionality
* Add unit tests for both backend and frontend
* Ability to change the name and logo of the site from admin panel.
* Make the installation process more interactive
* Add multiple theme support.

## License
[MIT License](https://github.com/ilmoislamnsu/SU19CSE299S02G01NSU/blob/master/LICENSE). Do whatever you would like to do! 😀


## Credits
I barely create the application. I just created the front end shell and done some integration with firebase. All the credits goes to all library creators and contributors to those libraries. I'm really grateful to all of them.

 - [React](https://facebook.github.io/react/)
 - [React Native](https://facebook.github.io/react-native/)
 - [React Native Animatable](https://github.com/oblador/react-native-animatable)
 - [React Native Scrollable Tab View](https://github.com/skv-headless/react-native-scrollable-tab-view)
 - [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
 - [Redux](https://github.com/reactjs/redux)
 - [React Redux](https://github.com/reactjs/react-redux)
 - [Redux Storage](https://github.com/michaelcontento/redux-storage)
 - [Redux Storage Engine - React Native Async Storage](https://github.com/michaelcontento/redux-storage-engine-reactNativeAsyncStorage)
 - [Firebase](https://firebase.google.com/)
 - [Moment JS](http://momentjs.com/)
 - [Lodash](https://lodash.com/)
 

Made by [Shafiqul Islam](https://github.com/ilmoislamnsu) and [Asha Das](https://github.com/AshaDas)
