Integrating with Swift
======================

This repository contains a simple sample app to show how to use Tag Commander's SDK in a Swift project.

The following steps have been taken in order to achieve that :

- Downloading the Core module and the SDK module from:

[our repository](https://github.com/TagCommander/pods)

- follow the explanation on the same page about :

[Importing Frameworks](https://github.com/TagCommander/pods#framework)


- Then check in this demo the file 

[AppDelegate.swift : application: didFinishLaunchingWithOptions:](SwiftCommanders/AppDelegate.swift)

Nothing very impressive here, what we can see is a basic example on how to import the frameworks, ask the SDK to display debug information, instanciate TagCommander and add some data to send them directly.

Next step
---------

Of course it is an example to show how it's possible and not a very good way to use our SDK. For that please read our complete documentation here :

[SDK documentation](https://github.com/TagCommander/pods/tree/master/TCSDK)

[Demo example in Objective-C](https://github.com/TagCommander/Tag-Demo/tree/master/iOS)

Special note on BITCODE
-----------------------

Tag Commander is not compiled with Bit Code enabled. So you will also need to desactivate it in your project. ENABLE_BITCODE = NO in your XCConfig file or in your project's build settings.

If you absolutly need a version of Tag Commander compiled with bitcode please contact us.
