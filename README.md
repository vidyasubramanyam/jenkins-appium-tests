# jenkins-appium-tests
Please refer to the [appium getting started](https://appium.io/docs/en/about-appium/getting-started/?lang=en) to start the new application

## The otehr links
[The follow the link for macbook](https://krishnachetan.medium.com/setup-appium-on-mac-1e06f1178427)


### Execute the commanns 

```
export JAVA_HOME=$(/usr/libexec/java_home)
export ANDROID_HOME=$HOME/Library/Android/sdk
echo $ANDROID_HOME
```
Install appium doctor and check everything looks good for Android
```
npm install -g appium-doctor
appium-doctor --android 
```

Run the appium server - stop appium if it is already running
```
killall node
appium &
```
