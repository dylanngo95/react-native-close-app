
# react-native-close-app

## Getting started

`$ npm install react-native-close-app --save`

### Mostly automatic installation

`$ react-native link react-native-close-app`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-close-app` and add `RNCloseApp.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCloseApp.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCloseAppPackage;` to the imports at the top of the file
  - Add `new RNCloseAppPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-close-app'
  	project(':react-native-close-app').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-close-app/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-close-app')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNCloseApp.sln` in `node_modules/react-native-close-app/windows/RNCloseApp.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Close.App.RNCloseApp;` to the usings at the top of the file
  - Add `new RNCloseAppPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNCloseApp from 'react-native-close-app';

// TODO: What to do with the module?
RNCloseApp;
```
  