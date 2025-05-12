# react native:
npx @react-native-community/cli init sadatcode
npx react-native run-android

rfce (react  native functional component3)
rnfes (React native functional export with styling(stylesheet))
# password Gen project:
npm i yup

formik: form er submit dekhay ...
npm install formik --save
npm i react-native-bouncy-checkbox


# backgroundChanger04:
android/local.properties     --- >  sdk.dir=G\:\\soft\\Sdk

 Error:
error Failed to install the app. Command failed with exit code 1: gradlew.bat app:installDebug 

Solution:
android folder -->  ./gradlew clean
remove  node modules folder and run "npm i" again 

# WIRELESS USB DEBGGING
adb pair 192.168.0.104:33181   //changes frequently ..
adb connect 192.168.0.104:39983

# RollTheDice
restart the bundler, when image imported ...
mp3, mp4, pdf, .html add korte Metro config korte hobe... 
"source" doesnot take a string, but and object (to add metadata(crop,left, right, transparency) to the obj ) ...
declare images as module.. index.d.ts ..

f
https://github.com/mkuczera/react-native-haptic-feedback
# npm i react-native-haptic-feedback
 npx react-native link react-native-haptic-feedback   x (wont work, will show error )

manual linking
android/app/src/main/java/MainApplication.java -->
           import com.mkuczera.RNReactNativeHapticFeedbackPackage;
           packages.add(new RNReactNativeHapticFeedbackPackage());

android settings.gradle -->
        include ':react-native-haptic-feedback'
        project(':react-native-haptic-feedback').projectDir = new File(rootProject.projectDir, '../node_modules/react-native-haptic-feedback/android')

x (not in github now)
android/app/build.gradle  (be careful, 2 build.gradle) --> in dependencies section  
        implementation project(":react-native-haptic-feedback")  x (not in github now)

Random : 
Button __ Touchable Opacity ...
 <Image source={{ uri: 'https://images.pexels.com/photos/6617495/pexels-photo-6617495.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load'
      }} 


type DiceProps = PropsWithChildren<{
  imageUrl: ImageSourcePropType
}>
    ({imageUrl}: DiceProps)

        <Image style={styles.diceImage} source={imageUrl} />


# / propsWithChildren .. we need a data of a particular type( .png) then we can use it

# Currency converter: 
1. /flatlist 
if you have long list of data ,use Flatlist instead of ScrollView
1000 items, screen can render only 6/7 items , flatlist will render only the visible ones in screen

2. /install Snackbar  (just a notification bar) 
npm install react-native-snackbar --save
 pod install --> coco pods , if you are in mac ,
return (
    <FlatList
    ref={(ref)=> {this.flatListRef = ref ; }}
    data = {data}>
)

js: 
if statement,  everything inside this component will be returned
{resultValue && ()}

# Project 7 : ticktack toe 
 react-native-vector-icons

1. npm install --save react-native-vector-icons

app/build.gradle for android
apply from: file("../../node_modules/react-native-vector-icons/fonts.gradle")

2. npm i @types/react-native-vector-icons

# music
react native track player 
npm install --save react-native-track-player

npm install @react-native-community/slider --save

# navigation 
pop screens (pages), 
after login, screenn goes away ...
dispatch  .. move to the second screen with some data  

npm install @react-navigation/native
npm install @react-navigation/native-stack



