React native expo CLI app

Instruction to run on local:

1. Download HelloWorld from repository

2. This is link to react native environment setup (steps and commands needed to make react native app run) :
https://reactnative.dev/docs/environment-setup?ref=retool.com&guide=quickstart

  This is needed make our react-native app runnable on andorid emulator, etc.
  
3. Enter HelloWorld app in terminal:
    cd HelloWorld
    
4. Use this command to start expo:
    npx expo start (use 'yarn expo start' if setup was in yarn)
    
5.1. When expo starts after previous command use 'a' keyboard button to start android emulator. (Or just use 'yarn android' to start android emulator with yarn)

5.2. Use 'npx expo install react-native-web@~0.18.10 react-dom@18.2.0 @expo/webpack-config@^18.0.1' to install react native web package
     After 'npx expo start' use 'w' keyboard button to run app on web or just use 'yarn web' with yarn (it will open app in browser, example like http://localhost:19006/)

