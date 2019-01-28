# Starting to Code

### 

When you are initially setting up and getting ready to start coding,  you may feel inclined to jump in quickly to start playing with everything, especially if you are new to React Native. If it is a practice app, jumping in is perfectly fine; however, once you are getting ready to add content to a REAL application, make sure your wireframe is on point. 

## Set up your navigation FIRST

I did a lot of trial and error in this process, and although I had a LOT to learn, my biggest takeaway is that a React Native app is dependent on the UI more than any other React Project that I had done before. You can't just link to a component the same way you do in a React Web App if you want to take advantage of the built in react-navigation functionality because it is all built on Higher Order Components. 

## Wireframe your User Scenarios on pen and Paper

If you do your planning, and have a good idea of what you want your app to look like, you can take advantage of the fact that the navigation prop is automatically sent to all of your screens. I decided that I did not like the tab navigation on the bottom of the screen for what I was building -- which was mostly an information app. I wanted the screen space reserved for content because most people using this application would use it on their mobile device. Instead, I did a drawer navigation which slides from the side. Click [here](#) for more information on how I implemented the Drawer Navigation in my app. 

## Dynamic Type

On Native applications, users have the option to make their overall device font size larger or smaller than the 'default' settings that we, (I),  may code to. For example, My phone's settings are set to normal font size. As I was developing this app and testing, I may have designed a button's text, or a Text Input with text to fit perfectly within it's bounds; however, when I change my phone's Dynamic Type setting to the largest font size, my button, which once said "Submit Referral" would then be cut off halfway saying, instead: "Submi". Obviously had I known that was going to be an issue, I would have developed with font size in mind. Luckily, there is a quick fix for this type of thing:

```js
<Text allowFontScaling={false}>This text will never change font size!</Text>
```

By setting the allowFontScaling prop to false, the text will not ever change, even if the user has their settings different than the 'defaults'.

PROS:
- 