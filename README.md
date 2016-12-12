# react-native-indicator

[![npm](https://img.shields.io/npm/dt/express.svg)](https://www.npmjs.com/package/react-native-indicator) ![react-native](https://img.shields.io/badge/react--native-0.38-brightgreen.svg) [![VersionEye](https://img.shields.io/versioneye/d/ruby/rails.svg)](https://github.com/wangdicoder/react-native-indicator) [![npm](https://img.shields.io/npm/v/npm.svg)](https://img.shields.io/badge/npm-3.10.9-red.svg) [![npm](https://img.shields.io/npm/l/express.svg)](https://www.npmjs.com/package/react-native-indicator)

A useful indicator component for React Native

## Installation

Make sure that you are in your React Native project directory and run:
```
$ npm install react-native-indicator --save 
```

### Android

It works, have fun!

### iOS

Add ```ART.xcodeproj``` from ```node_modules/react-native/React/Libraries/ART``` to your Libraries then link ```libART.a```. To see more details about **Linking Libraries**, jump to [this](https://facebook.github.io/react-native/docs/linking-libraries-ios.html).

## Usage

Import react-native-indicator as a JavaScript module:
```
import {CirclesLoader, PulseLoader, TextLoader, DotsLoader, ...} from 'react-native-indicator';
```

Here is currently available types: 

- PulseLoader
- DotsLoader
- TextLoader
- BubblesLoader
- CirclesLoader
- BreathingLoader
- RippleLoader
- LinesLoader
- MusicBarLoader

```
render(){
    return(
        <View>
            <CirclesLoader />
            <TextLoader text="Loading" />
        </View>
    ); 
}
```

## Props

##### PulseLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 10 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |


##### DotsLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 10 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |
| betweenSpace | number | 5 | no | the distance between two dots |


##### TextLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| **text** | string | none | **yes** | contents |
| textStyle | style | inherited | no | text's style |


##### BubblesLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 40 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |
| dotRadius | number | 10 | no | each dot's size |


##### CirclesLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 40 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |
| dotRadius | number | 8 | no | each dot's size |


##### BreathingLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 10 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |
| strokeWidth | number | 3 | no | outline width |
| frequency | number | 800 | no | scale's frequency |


##### RippleLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| size | number | 10 | no | circle's size |
| color | string | '#1e90ff' | no | the indicator's color |
| strokeWidth | number | 3 | no | outline width |


##### LinesLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| color | string | '#1e90ff' | no | the indicator's color |
| barWidth | number | 5 | no | each bar's width |
| barHeight | number | 40 | no | each bar's height |
| barNumber | number | 5 | no | the number of bar |
| betweenSpace | number | 2 | no | the distance between two bars |


##### MusicBarLoader

| prop | type | default | isRequired | description |
| ---- | ---- | ---- | ---- | ---- |
| color | string | '#1e90ff' | no | the indicator's color |
| barWidth | number | 3 | no | each bar's width |
| barHeight | number | 30 | no | each bar's height |
| betweenSpace | number | 5 | no | the distance between two bars |


## License

MIT