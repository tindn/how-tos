## Change default splash screen color

### iOS
- Update the LaunchScreen.storyboard file by changing the background color
  - In XCode, selects the LaunchScreen.storyboard file to open the designer
  - Select the main View, and select the Attributes inspector in the right pane
  - Select the background color from the Attributes inspector pane

- Update Status Bar Style option in either XCode (under the General tab) or directly in the Info.plist file.

- Update the background color of the app in `AppDelegate.m`

### Android
- Update the app theme by adding the following in the `src/main/res/values/styles.xml` file.
```xml
<item name="android:windowBackground">#dddddd</item>
```
  