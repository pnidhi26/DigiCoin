## NFT Mobile/iOS App

* Scan the below QR to download this App:
  
![image](https://github.com/pnidhi26/DigiCoin/assets/30867614/3e72b8e2-30bb-40b4-ac3d-012bbd81de7e)

![image](https://github.com/pnidhi26/DigiCoin/assets/30867614/ff698e0c-6607-4884-a155-7bed75edae17
![image](https://github.com/pnidhi26/DigiCoin/assets/30867614/1642c439-dd92-4ec9-a3f7-989166d65810)


## Tech Stack Used:
 - React Native, React navigation, Expo Go, 


## cmd to install required dependencies:
* expo init ./
* npm install --legacy-peer-deps
* npm audit fix


## Run Server on Local:
* npm start
* Scan QR code on Expo Go app

## Build and Deployment:
- Classic SDK < 49
* npm install expo@latest expo-cli@latest
* npx expo-cli publish

- EAS SDK > 50
* npm install --global eas-cli
* eas login
* eas update:configure
* eas build:configure
* eas build
* eas update
