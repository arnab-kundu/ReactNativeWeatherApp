# react-native-weather-app

## Tech Used

React Native, Styled-Components

## The UI

<img src="" alt="The User Interface" width="450"/>


## How To Run The App in an IOS Simulator

#### Step 1: 
- Clone the repo
- Open it in your favorite editor
- Open a terminal in your editor and run `yarn install`

#### Step 2: 
- Head over to https://openweathermap.org/api/one-call-api to get an API key. (You will have to sign up)
- Head over to https://developers.google.com/maps/documentation/geocoding/overview to get a GEOCODING API key. You will have to follow the instructions on that page. I am using this to get the `Lat` and `Long` from the postal code since Open Weather API accepts only zip codes.
- Create a `.env` file in the root folder and put your keys in the file like this: 

```
API_KEY=YourOpenWeatherKeyHere
GOOGLE_KEY=YourGoogleKeyHere
```

#### Step 3:

- Download xcode 
- In the menu bar go to Xcode -> Open Developer Tools -> Simulator

#### Step 4: 

- In your terminal run `yarn start`. 
- In the browser, click on `Run on IOS Simulator`.

## Dependencies 

```json
"dependencies": {
    "react": "18.2.0",
    "react-native": "0.73.5",
    "expo-status-bar": "^1.11.1",
    "moment": "^2.30.1",
    "react-dom": "^18.2.0",
    "react-native-dotenv": "^3.4.11",
    "react-native-web": "^0.19.10",
    "styled-components": "^6.1.8"
  },
  
  ```
