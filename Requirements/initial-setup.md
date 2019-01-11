# Setup using Expo and React Native





## Before you begin: 

- You will need to have Node.js (v10 or newer) installed on your computer.
- If you have never used Expo, you will need to install the Expo CLI for Local Development, and The Expo Mobile Client for iOS and Android in order to view your project while you are developing. For more information, head over to the Expo Installation Docs [here](https://docs.expo.io/versions/latest/introduction/installation.html).
    -   *For this project, I solely used the Expo Mobile Client App for viewing/testing during development. There are other ways to watch your apps during development.* 
    - Pro Tip: you can use the Apple Simulator to test your app on multiple device environments before testing on the actual device.


## Ready to Go?

I used the [Up and Running](https://docs.expo.io/versions/v32.0.0/workflow/up-and-running) Guide on the [Expo Docs](https://docs.expo.io/versions/latest/) to set up this React Native Application. If you know anything about React Native, you know that the way you initialize a React Native App can determine whether you will run into issues down the road when you are trying to install and run dependencies, and generally debug. After some trial and error, I decided this flow was the best way to create the project to get everything working cohesively. :) 

Feel free to follow along here, or go to the [docs](https://docs.expo.io/versions/v32.0.0/workflow/up-and-running) for a more detailed explanation.

1. In your terminal, navigate to the location on your computer where you would like to create your project.
2. Run `expo init` to create your project
    ```bash 
    $ expo init
    ```
    You will be asked to name your project, and then asked to choose a project template. If you are new to React Native, choose the `tabs` option to give you a good starting point -- this includes tab navigation. Even if you decide to change the navigation options, this will help you to figure out the file structure.
    You can choose 'Y' to use yarn to install dependencies, or if you are like me, You can choose 'N' to use npm.

    Your project will start to build and can take a few minutes.
    