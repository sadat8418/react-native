# react native:
npx @react-native-community/cli init sadatcode
npx react-native run-android

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
npm i react-native-haptic-feedback
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
