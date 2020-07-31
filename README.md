
# react-native-alina-lib-new

## Getting started

`$ npm install react-native-alina-lib-new --save`

### Mostly automatic installation

`$ react-native link react-native-alina-lib-new`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-alina-lib-new` and add `RNAlinaLibNew.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNAlinaLibNew.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNAlinaLibNewPackage;` to the imports at the top of the file
  - Add `new RNAlinaLibNewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-alina-lib-new'
  	project(':react-native-alina-lib-new').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-alina-lib-new/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-alina-lib-new')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNAlinaLibNew.sln` in `node_modules/react-native-alina-lib-new/windows/RNAlinaLibNew.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Alina.Lib.New.RNAlinaLibNew;` to the usings at the top of the file
  - Add `new RNAlinaLibNewPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNAlinaLibNew from 'react-native-alina-lib-new';

// TODO: What to do with the module?
RNAlinaLibNew;
```
  