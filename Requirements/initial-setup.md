# Setup using Expo and React Native





## Before you begin: 

- You will need to have Node.js (v10 or newer) installed on your computer.
- If you have never used Expo, you will need to install the Expo CLI for Local Development, and The Expo Mobile Client for iOS and Android in order to view your project while you are developing. For more information, head over to the Expo Installation Docs [here](https://docs.expo.io/versions/latest/introduction/installation.html).
    -   *For this project, I solely used the Expo Mobile Client App for viewing/testing during development. There are other ways to watch your apps during development.* 
    - Pro Tip: you can use the Apple Simulator to test your app on multiple device environments before testing on the actual device.


### Ready to Go? 
## Setting up your app

I used the [Up and Running](https://docs.expo.io/versions/v32.0.0/workflow/up-and-running) Guide on the [Expo Docs](https://docs.expo.io/versions/latest/) to set up this React Native Application. If you know anything about React Native, you know that the way you initialize a React Native App can determine whether you will run into issues down the road when you are trying to install and run dependencies, and generally debug. After some trial and error, I decided this flow was the best way to create the project to get everything working cohesively. :) 

Feel free to follow along here, or go to the [docs](https://docs.expo.io/versions/v32.0.0/workflow/up-and-running) for a more detailed explanation.

1. In your terminal, navigate to the location on your computer where you would like to create your project.
2. Run `expo init` to create your project
    ```bash 
    $ expo init
    ```
    You will be asked to name your project, and then asked to choose a project template. If you are new to React Native, choose the `tabs` option to give you a good starting point -- this includes tab navigation. Even if you decide to change the navigation options, this will help you to figure out the file structure.
    You can choose 'Y' to use yarn to install dependencies, or if you are like me, You can choose 'N' to use npm.

    Your project will start to build and can take a few minutes and then Voila, you officially have a React Native App. Now, on to running it...
    
    
## Running your app

### In order to watch your app as you are developing...

Navigate inside of you project folder and run one of the following 3 commands (I prefer `expo start`): 
```bash 
$ expo start
$ npm start
$ yarn start
```

This command will open up your the Metro Bundler on localhost in your default browser. 

In both the terminal and browser windows, a QR code is displayed that links to your Expo Mobile Client app. Open up your camera app on your phone and scan the code - your phone will ask if you'd like to open your project in the Expo app. 

More information is displayed in the terminal about running the app with live reloading. I highly recommend signing in with your expo username in the app - that way, there is no need to scan the QR code every time.

> *Hint: In order to use a LAN connection(default) you must be on the same wifi network on your computer and devices. Otherwise, you will have to create a tunnel connection.*

Once you are connected and open your project, you can see that expo has created an application for you with bottom tab navigation. Now you are ready to make it your own! As you make edits in your text editor and save, your app will automatically reload 
