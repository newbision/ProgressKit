
![ProgressKit Banner](/Images/banner.gif)

[![Cocoapods Compatible](https://img.shields.io/cocoapods/v/ProgressKit.svg)](https://img.shields.io/cocoapods/v/ProgressKit.svg)
[![Platform](https://img.shields.io/cocoapods/p/ProgressKit.svg?style=flat)](http://cocoadocs.org/docsets/ProgressKit)
[![License](https://img.shields.io/cocoapods/l/ProgressKit.svg?style=flat)](http://cocoadocs.org/docsets/ProgressKit)



`ProgressKit` has set of cool `IBDesignable` progress views, with huge customisation options. 
You can now make spinners, progress bar, crawlers etc, which can be finely customised according to your app palette.

# Contents
- [Installation](#installation)
- [Usage](#usage)
- [Indeterminate Progress](#indeterminate-progress)
  - [MaterialProgress](#MaterialProgress)
  - [Rainbow](#rainbow)
  - [Crawler](#crawler)
  - [Spinner](#spinner)
  - [Shooting Stars](#shooting-stars)
  - [Rotating Arc](#rotating-arc)
- [Determinate Progress](#determinate-progress)
  - [Circular Progress](#circular-progress)
  - [Progress Bar](#progress-bar)
- [Other Apps](#other-apps)
- [License](#license)

# Installation
##CocoaPods
[CocoaPods](http://cocoapods.org) adds supports for Swift and embedded frameworks.

To integrate ProgressKit into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
use_frameworks!

pod 'ProgressKit'
```
For Swift 3 install directly from `swift-3` branch form github

```ruby
pod 'ProgressKit', :git => "https://github.com/kaunteya/ProgressKit.git", :branch => 'swift-3'
```

Then, run the following command:

```bash
$ pod install
```
  
# Usage
- Drag  a View at desired location in `XIB` or `Storyboard`
- Change the Class to any of the desired progress views
- Set the size such that width and height are equal
- Drag `IBOutlet` to View Controller
- For `Indeterminate` Progress Views
  - Set `true / false` to `view.animate`
- For `Determinate` Progress Views:
  - Set `view.progress` to value in `0...1`
  

# Indeterminate Progress

![Indeterminate](/Images/indeterminate.gif)  
Progress indicators which animate indefinately are `Indeterminate Progress` Views.

This are the set of Indeterminate Progress Indicators.

## MaterialProgress
![CircularSnail](/Images/CircularSnail.gif)

## Rainbow
![Rainbow](/Images/Rainbow.gif)
## Crawler
![Crawler](/Images/Crawler.gif)

## Spinner
![Spinner](/Images/Spinner.gif)

## Shooting Stars
![Shooting Stars](/Images/ShootingStars.gif)

## Rotating Arc
![Rotating Arc](/Images/RotatingArc.gif)

# Determinate Progress
Determinate progress views can be used for tasks whos progress can be seen and determined.

## Circular Progress
![Circular Progress](/Images/CircularProgress.png)

## Progress Bar
![Progress Bar](/Images/ProgressBar.png)

# Other Apps

## Lexi
Lexi is a split screen app that lets you browse large JSON with ease.

It also has other featuers like `Prettify JSON`, `Minify JSON` `Copy JSON Path` and `Pin Large JSON` to narrow your visibility

[View on Mac AppStore](https://itunes.apple.com/us/app/linex-for-xcode/id1290932760?ls=1&mt=12) 

## Quick Note - A click menubar notes
Quick Note lets you quickly add text either from Menu bar or from Shortcut.

The text floats on other windows so that they are always visible

It also supports `Auto Save` and `Pinned Notes`

[View on Mac AppStore](https://apps.apple.com/in/app/quicknote-one-click-notes/id1472935217?mt=12) 



# License
`ProgressKit` is released under the MIT license. See LICENSE for details.

