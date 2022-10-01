# AASwiftUtils
A CocoaPods open source library written in Swift. It has the all common functions and utilities required to develop an app.

As Swift evolves, if you are not using latest Swift compiler, you shouldn't check out master branch. Instead, you should go to release page and pick up whatever version suits you.

- Xcode 10.0 / Swift 4.2 (master branch)
- iOS >= 9.0

# Having trouble? Ask questions & issues

If you are having questions or problems, you should:

Make sure you are using the latest version of the library. Check the release-section.
- Read the usase
- Search or open questions on stackoverflow with the AAUtil tag
- Search known issues for your problem (open and closed)
- Create new issues (please search known issues before, do not create duplicate issues)

# Usase

Create an object of AASwiftUtils class.
- var aaUtils: AASwiftUtils!

Initialize
- aaUtils = AASwiftUtils()
- aaUtils.showAlert(title: "Title", message: "Test message..", controller: self)
- aaUtils.printLog("Test log..")
- aaUtils.month(from: Date())

# Features

Core features:
- Show alert dialog.
- Validate email field.
- Validate phone number field.
- Validate password field.
- Get path of app document directory.
- Get device token string.
- Print log in console, only in debug mode.
- Get month name from date.
- Get day from date.
- Get year from date.
