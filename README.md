<p align="center">
    <img width="90" height="90" src="https://i.ibb.co/T1CdkGm/insta.jpg">
</p>

# InstagramClone

> A clone of the Instagram app (Jul 2024) made with React, React-native and Typescript.

## Preview

![App-demo](./src/screenshots/Demo.gif)

## Screen (Home)

![App-demo](./src/screenshots/Demo1.png)

## Screen (Profile)

![App-demo](./src/screenshots/Demo2.png)

## Screen (Gallery)

![App-demo](./src/screenshots/Demo3.png)

## Screen (Camera)

![App-demo](./src/screenshots/Demo4.png)

## Screen (Story)

![App-demo](./src/screenshots/Demo8.png)

## Screen (Comments)

![App-demo](./src/screenshots/Demo5.png)

## Screen (Search By Tag)

![App-demo](./src/screenshots/Demo7.png)

## Screen (-#-)

![App-demo](./src/screenshots/Demo6.png)

### Dependencies

- React Native (With Typescript)
- Native Base
- React Navigation
- Others (See package.json at the root folder)

## Get Started

#### 1. Clone the Repo

On the command prompt run the following commands

```sh
$ git clone https://github.com/thetinshusasi/insta_clone.git

$ cd InstagramClone

$ npm install

$ grep -rl "s.dependency 'React/Core'" node_modules/ | xargs sed -i '' 's=React/Core=React-Core=g' // To replace React/Core with React-core for all dependencies that use it

$ cd ios && pod install && cd..

$ react-native run-ios

```

## Author

- [Tinshu Sasi](mailto:thetinshusasi@gmail.com)

  [![Linkedin: tinshu-sasi](https://img.shields.io/badge/-Tinshu%20Sasi-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tinshu-sasi/)](https://www.linkedin.com/in/tinshu-sasi/)
