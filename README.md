# Shawn's Scouting - Flutter UI

**Introduction:**

Shawn's Scouting app is the people’s choice for review the dog walker services and rating the company according to their services. In the Shawn’s scouting app dog walker service provider will signup and add their company details  get listed on shawn’s scouting  to be a part of a prolific & elite group of dog walker service providers. Further enhance your online presence for improved ROIs and expand your business. Ask your customers to leave review for your services and these verified & unbiased reviews from authenticated customers will help you to gain trust of prospective clients.
We provide the most clinical and genuine platform to showcase your business as top dog walker’s app development companies. Make sure your business is found when decision makers are searching.


**Table of Contents:**

**Overview**

**Goals**

**Why Flutter?**

**Dart Language**

**Flutter Packages**

**Folder Structure**

**How to install Shawn’s Scouting APK in android**

**How to install Shawn’s Scouting  IPA file in IOS**

**Overview :-**

Shawn's Scouting - Flutter UI is a Flutter UI using which you can develop beautiful Mobile Apps for Android & iOS.
Shawn's Scouting industry is expected to grow to over 2 billion dollars by 2022. Seeing the industry trend, Deligence Technologies’ team has developed a dog Walker’s app template using Flutter technology, for developers and Apprenuers who may seek to invest in dog walker’s App development. The template is compatible with both iOS and Android.

**Goals :-**

Develop dog's service provider App with seamless UI/UX design for Android and iOS platform. 	

**What you will get here :-**
 	
This template is a fixed layout with flutter widgets. It contains a complete UI design for dog walker service providers application for mobile platforms, both android as well as ios.
 	
You will also get access to the code responsible for the UI design.
 	
This template demonstrates UI animations and the functionality of find companies by  location, filter companies by country, lower rating, higher rating and companies by alphabet in the template.
 	
You can edit/modify or add code as per your requirements.
Example 1:

If you would like to edit the color of any text, icon and theme elements in one of these columns, you would replace this code:
 	
 go to :shwan/lib/color/color.dart

Color primaryColor = Colors(0xffEEA150)
	 
   With

Color primaryColor = Colors(‘which colour you want to replace’)

Example 2:
We are creating models for dynamic data like company details, company services,  If you would like to edit any text, icon,theme elements and add new company statically in models, you would do the following:
 go to :shawn/lib/models/fileName.dart
Text(‘Shawn’s Scouting’’)	 
   With
Text(‘some text here you want to write’)



**Why Flutter -**

We have used flutter as hybrid mobile application development framework.
Flutter is a free and open source Google mobile UI framework that provides a fast and expressive way for developers to build native apps on both IOS and Android.

**Fast development**

Flutter engineered for high development velocity. Stateful hot reload allows you to change your code and see it come to life is less than a second without losing the state of the app. Flutter also ships with a rich set of customizable widgets, all built from modem reactive framework.

**Expressive + Flexible UI**

Flutter moves to a widget, rendering, animation and gestures into this framework to give you complete control over every pixel on the screen. It means you have the flexibility to build a custom design.

**Native apps for Android and IOS**

Flutter apps follow platform conventions and interface details such as scrolling, navigation, icons, fonts, etc. That's why apps built with Flutter features on both of the APPSTORE and GOOGLE PLAY STORE.

**High Performance**

Flutter doesn’t require a Javascript bridge and the speed is much faster.

For full documentation regarding flutter visit: https://flutter.dev/docs




**Dart Language -**

In this template we are using dart language. Dart is an object-oriented programming language. Dart is used for writing mobile application code for Flutter. It contributes to the efficiency and effectiveness of app development flow.

Dart uses for generational garbage collection which helps in creating frames for short-lived objects. It also helps to allocate the objects with a single pointer bump to avoid UI jack and shutter.


For full documentation regarding Dart language visit : https://dart.dev/guides


**Flutter Packages-**
 
Flutter supports using shared packages contributed by other developers to the Flutter and Dart ecosystems. This allows quickly building an app without having to develop everything from scratch.
The Flutter landing page on https://pub.dev displays top packages that are compatible with Flutter (those that declare dependencies generally compatible with Flutter), and supports searching among all published packages.
In this template we have used multiple  package like simple animation,image picker, flutter rating bar and  flutter map etc  which is available in flutter packages.


**Simple Animation -**

In this template we have used simple animation package which is available in flutter packages.
name: simple_animations
version used: simple_animations: ^1.3.4

**Features:**

AnimationControllerX a new, powerful AnimationController
AnimationControllerMixin to easily setup AnimationControllerX
5 types of AnimationTasks to use for AnimationControllerX
ControlledAnimation: Widget for simple tween-based custom animations
MultiTrackTween: Animatable for tweening multiple properties at once

For more information visit: https://pub.dev/packages/simple_animations


**Flutter Rating bar-**

In this template we have used flutter rating bar package which is available in flutter packages.
name: flutter_rating_bar
version used: flutter_rating_bar: ^3.0.1+1
customizable rating bar for flutter which also include a rating bar indicator, supporting any fraction of rating.

**Salient Features: **

Set minimum and maximum rating
Any widgets can be used as as rating bar/indicator items
Different widgets can be used in same rating bar as per position
Supports vertical layout
Glows on interaction

For more information visit: https://pub.dev/packages/flutter_rating_bar

**Flutter Map -**

In this template we have used Flutter map box package which is available in flutter packages.
name:flutter_map
version used: flutter_map: ^0.8.2
Flutter map  is a flutter plugin to find available maps installed on a device and launch them with a marker for specified location. Flutter map is using Leaflet mapbox  for  app.

Mapbox provide a map and  marker, you can change center location and marker location of companies by new lat and long. In the shawn’s Scouting app  we can also  get current location of the user and give direction for company loction. 

For more information visit: https://pub.dev/packages/flutter_map

For full documentation regarding flutter packages visit : https://flutter.dev/docs/development/packages-and-plugins/using-packages	


**Folder Structure-**

There are 3 Folders -
All Code - which contains all the code
APPs - The iOS & Android App (The App will show you the designs only, these are not fully functional apps)
Support - It contains Documentation.

Main folders in lib section (inside All Code folder):-

models  :  consists of model classes for setting company details, company service details  and client review.
screen  :  screen consists of User Interface(UI) design of app. Screen Folder contains subfolders like auth, reminder. 	


auth :  auth provides login screen, signup screen and forget password screen.
Color : Color contains two files, one file is color.dart in which theme color is set and another one is styleTheme file which contains text style of theme

There other functionality available in screens folder like details, edit-profile, explore, home screen, invite friends, stories and welcome screen. If you would like to edit the text , image , icon and theme elements in one of these columns, you would do the following:
 	
To change text style and value in file:
	 
static const TextStyle headline = TextStyle(fontSize: 24, color: Colors.black, fontWeight: FontWeight.bold);
With
static const TextStyle headline = TextStyle(fontSize: fontSize, color:fontColorWhichYouWant, fontWeight: FontWeightName);

To change image name in file:
Save image in appFolder/asset/img.
Open pubspec.yaml file and add image path in assets:
asset/image/imageName.extension
Open file where you want to display new image and replace -
Asset(‘asset/img/abc.jpg’)
	With
Asset(‘folderName/ImageName.extension’)			
	
Animation :   Animation folder contains class files for customising animation for whole app. 
	 	
		
**How to install Shawn’s Scouting APK in android -**

**What is an APK File?**

An Android Package Kit (APK for short) is the package file format used by the Android operating system for distribution and installation of mobile apps. Just like Windows (PC) systems use an .exe file for installing software, the APK does the same for Android.

How to install APK File from your Android device?
Get the apk from APPs folder (app-release.apk)

tap on the APK file, and tap Yes when prompted.
The app will begin installing on your device. Simple.
 How to install Shawn’s Scouting IPA file in IOS -

**What is an IPA file?**

A file with the IPA file extension is an iOS App file. They function as containers (like ZIP) for holding the various pieces of data that make up an iPhone, iPad, or iPod touch app; like for games, utilities, weather, social networking, news, and others

How to install IPA File using Xcode

Get the IPA file from APPs folder (Runner.ipa)
You can install your iOS app (.ipa file) via Xcode as follows:
Connect your device to your PC.
Open Xcode, go to Window → Devices .
Then, the Devices screen will appear. Choose the device you want to install the app on.
Drag and drop your .ipa file into the Installed Apps
