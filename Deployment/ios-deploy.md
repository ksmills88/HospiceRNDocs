https://codeburst.io/how-to-deploy-a-create-react-native-app-to-the-appstore-229a8fa36fb1


# iOS

## Running a Build / Deploying to the App Store

#### Steps:
1. Run a build the app locally
2. Use Application Builder (or equivalent) to load version to either the App Store(TestFlight during testing).
3. Update your app in App Store(TestFlight during testing).

When ready to build the version to the app store, run this command in your terminal. 

- *Make sure the code is up to date and you have provided the correct version information in your app.json*

```node
$ expo build:ios
```
-   The build usually takes at least a few minutes (for my simple informational app with minimal functionality, it averages about 3 minutes).

-   While building, terminal outputs information about how to track your build. Use that if you want to. I usually wait for the build to complete. 

-   Once build is complete, URL is provided via Terminal to access the download file. Click on provided URL
```node
Looks like this: https://expo.io/builds/buildreferencenumber
```
Clicking on this will initiate an automatic download to your computer. You will load this file 