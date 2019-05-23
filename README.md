# Lottie-Example-Swift
## This ia Cocopods  tutorial
![May-20-2019 16-51-56](https://user-images.githubusercontent.com/2945947/58109761-341e9b80-7bbc-11e9-805d-0782093c411f.gif)
#### 1. The resource I am using
[airbnb lottie-ios] https://github.com/airbnb/lottie-ios#dynamic-animation-properties

#### 2. Install CocoaPods

#### 3. How to use CocoaPods
* create a Xcode project but don't work on it right away
* direct to the project folder in the Terminal and initial a pod by typing
```
pod init
```
* edit a Podfile, here we add pod 'lottie-ios'
```
platform :ios, '9.0'

target 'Lottie-Example-Swift' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Lottie-Example-Swift
  pod 'lottie-ios'

  target 'Lottie-Example-SwiftTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'Lottie-Example-SwiftUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
```
* In the Terminal, type in pod install and wait for a workspace related with Xcode project be created.
```
pod install
```
* open Lottie-Example-Swift.xcworkspace to start working on the code
<img width="150" alt="workspace-logo" src="https://user-images.githubusercontent.com/2945947/58110404-74cae480-7bbd-11e9-8a07-44058fd7a241.png">

#### 4. How to use Lottie CocoaPod
From now on, we can use the information from [airbnb github page](https://github.com/airbnb/lottie-ios#dynamic-animation-properties) to use the animation feature.
In this project, I downloaded free lottie animation file 30-brghtness.json from [LottieFiles.com](https://lottiefiles.com) and added simple code in the viewDidLoad() function of ViewController.swift. And **DONE!** It will save your tons of time to do the fancy work. Love it? Try it by yourself then.
