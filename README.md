# Set up project:

## One time expo setup
1. Install node.js
2. Open terminal: ```npm install -g expo-cli```
3. Check version with ```expo --version```

## Run project
4. Clone the repo
5. (make sure ur in project folder) and run ```npm install``` to recognize it as a project
6. to run app: ```npx expo start```

## Build
Option 1. Physical Android Device
- Download the Expo Go App
- Scan the QR Code generated by ```npx expo start```

Option 2. Virtual Android Device
- Download Android Studio
- Create a virtual device
- Open the virtual device
- Press A after ```npx expo start```

## Known Errors & Fixes
If you get connection error after scanning the qr code try ```npx expo start --tunnel```







## Command TO START THE SERVER for BOT and Testing 
- go to directory of index.js and run 'node index.js' or we can use the run button if the ide is VSC
(Need to have nodes library installed )
- run 'ngrok http 3333' to expose the local server
(Need to have ngrok installed, one problem have to copy and paste fulfilment secton in Dialogflow)

