
# react-native-smart-swipe

## Getting started

`$ npm install react-native-smart-swipe --save`

### Mostly automatic installation

`$ react-native link react-native-smart-swipe`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-smart-swipe` and add `RNSmartSwipe.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSmartSwipe.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.nghinv.smartswipe.RNSmartSwipePackage;` to the imports at the top of the file
  - Add `new RNSmartSwipePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-smart-swipe'
  	project(':react-native-smart-swipe').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-smart-swipe/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-smart-swipe')
  	```


## Usage
```javascript
import RNSmartSwipe from 'react-native-smart-swipe';

// TODO: What to do with the module?
RNSmartSwipe;
```
  