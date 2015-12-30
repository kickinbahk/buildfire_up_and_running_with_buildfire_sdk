## Up and Running with BuildFire SDK

The BuildFire SDK allows for developers to make plug-ins that can be used and sold on the BuildFire platform and in BuildFire apps. This allows for developers to be able to adapt BuildFire to the specific use case of a customer or fill a need which BuildFire has not already filled.

To get started with you should start by signing up for a developer account at [developer.buildfire.com](http://developer.buildfire.com).

[Image of developer portal]

Once signed up, you will need to get the SDK locally on your machine. This will allow you to begin developing in your IDE or editor.

To get the SDK, you then can either download the zip file from the [developer.buildfire.com](http://developer.buildfire.com) page or you can fork the [repo](https://github.com/BuildFire/sdk).

If you fork the repo, you will need to <code>git clone</code> the repository into the folder you want on your machine.

Go ahead and open up the sdk folder should now be local on your machine. You can use any IDE or text editor you prefer. Though, having a webserver built in to your environment is nice so you can test the plug-in locally and see the changes you are making to it. A couple recommendations of some IDEs to maybe use would be Webstorm or Brackets, as both have this functionality.

Once you have the SDK open, you will want to grab the App Id from your developer portal. This App Id is what we issue you to be able to test your plug-in. 

[Image where to find App Id]

After grabbing the App Id, you should change the App Id in the <code>window.appContext.currentApp</code>. This will allow you to start testing your app.

Before we end, let's make sure we are all set by actually running our plug-in locally.

In the SDK, navigate to the 'pluginTester' directory, then to the <code>index.html</code> file inside it and choose to open it in the browser or run it.

This should bring up the developer dashboard confirming you are ready to start developing your app!

![Image of Developer Dashboard on localhost](../dev-dashboard.png)



