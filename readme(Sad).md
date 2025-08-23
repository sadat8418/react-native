# react native:

npx @react-native-community/cli init sadatcode
npx react-native run-android

   IPv4 Address. . . . . . . . . . . : 192.168.1.106
# Before deleting the project, run:

cd android
 ./gradlew cleanBuildCache
./gradlew --stop
5. ./gradlew clean

# npx react-native doctor
01: Aewsome, sadatCode
02: 
03: passwordGen
04: bgChanger
05: roll the dice
06: CurrencyConverter, X
07:tictactoe 
08: spotifymusic, music
09:navigation
10:shopping
11:appwrite


RESTART THE FUCKING PC
ANDROID_HOME
JAVA_HOME : C:Program Files/ Micorsoft{or Openlogic} \ jdk-17.0.13.11
build-tool , platforms extra dise

# Delete node modules , gradle
1. Remove-Item -Recurse -Force .\node_modules\

2. Remove-Item -Recurse -Force . package-lock.json  

3. cd android
4. ./gradlew --stop
5. ./gradlew clean


# ERROR
1.  A problem occurred configuring root project 'X'.
> Could not resolve all dependencies for configuration 'classpath'.
# chatgpt .. C:\Windows\System32\drivers\etc\hosts  " 127.0.0.1 dl.google.com =" delete 
C:\Users\Just Work\AppData\Local\Android

2. Error : Long path name [problem]
gradle.properties --> android.overridePathCheck=true

3. UPDATE GRADLE:
graddle-wrapper.properties
distributionUrl=https\://services.gradle.org/distributions/gradle-8.14.3-bin.zip

4. kotlin issue 
Kotlin 2.1.20 → This is too new and not supported by the Android Gradle Plugin or react-native-track-player v4.1.2.

update kotlin, clean gradle, 


rfce (react  native functional component3)
rnfs
rnfes (React native functional export with styling(stylesheet))

# files 
__tests__
builld.gradle -->  sometimes dependencies manually input dei
# android/locale.properties --> sdk.dir=G\:\\soft\\Sdk
# create src/App.tsx
fix index.js ==> src/App.tsx
for ios --> Podfile
.watchman --> constantly reupdates the ui ,reuploads 
#in babel --> metro (in react antive)---> just like bundlers that combines all js files & make it available for browser & mobile 

tsconfig 

<SafeAreaView>, <View>, Text(for text),
Stylesheet
useColourScheme

flex: 1
align-items-- left to right
justify-content -- top top bottom 

<ScrollView>

# password Gen project 03:
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

# RollTheDice 05
restart the bundler, when image imported ...
mp3, mp4, pdf, .html add korte Metro config korte hobe... 
"source" doesnot take a string, but and object (to add metadata(crop,left, right, transparency) to the obj ) ...
# declare images as module.. # index.d.ts ..
<imageSourcePropType>  --> image chay /a.png something

https://github.com/mkuczera/react-native-haptic-feedback
# npm i react-native-haptic-feedback
 npx react-native link react-native-haptic-feedback   x (wont work, will show error )

# manual linking
android/app/src/main/java/MainApplication.java -->
           import com.mkuczera.RNReactNativeHapticFeedbackPackage;
           packages.add(new RNReactNativeHapticFeedbackPackage());

android settings.gradle -->
        include ':react-native-haptic-feedback'
        project(':react-native-haptic-feedback').projectDir = new File(rootProject.projectDir, '../node_modules/react-native-haptic-feedback/android')

x (not in github now)
android/app/build.gradle  (be careful, 2 build.gradle) --> in dependencies section  
        implementation project(":react-native-haptic-feedback")  x (not in github now)


# Currency converter 06: 
1. /flatlist 
if you have long list of data ,use Flatlist instead of ScrollView
1000 items, screen can render only 6/7 items , flatlist will render only the visible ones in screen

2. /install Snackbar  (just a notification bar) 
npm install react-native-snackbar --save
(LINKING LAGBE)
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
3. react-native-snackbar

npm i --save-dev @types/react-native-vector-icons
# music08 (track player )
1. npm install --save react-native-track-player

    npm install react-native-track-player@^3.2.0

2. npm install @react-native-community/slider --save
3. npm install --save react-native-vector-icons

4. npm i @types/react-native-vector-icons
musicPlayerService.js


# gradle-plugin missing
npm install @react-native/gradle-plugin

# navigation 
pop screens (pages), 
after login, screenn goes away ...
dispatch  .. move to the second screen with some data  

npm install @react-navigation/native
npm install @react-navigation/native-stack
npm install react-native-screens react-native-safe-area-context
# kotlin ERROR MainActivity.kt
import android.os.Bundle
  override fun onCreate(savedInstanceState: Bundle?) {
    super.onCreate(null)
  }
# nav-Shopping
same as  #navigation

# Random : 
PropsWithChildren --> specific type pass korte 
Button __ Touchable Opacity ...
 <Image source={{ uri: 


type DiceProps = PropsWithChildren<{
  imageUrl: ImageSourcePropType
}>
    ({imageUrl}: DiceProps)

        <Image style={styles.diceImage} source={imageUrl} />


# / propsWithChildren .. we need a data of a particular type( .png) then we can use it

gradlew.bat
set CLASSPATH=%APP_HOME%\gradle\wrapper\gradle-wrapper.jar

activity Indicator : loading circle