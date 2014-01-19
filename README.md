PowerPoint-Remote Server
========================

The server for [PowerPoint Remote](https://github.com/theporenta/powerpoint-remote).

# What this is

This is a PowerPoint-AddIn that is required to use the [PowerPoint Remote](https://github.com/theporenta/powerpoint-remote) Android App written by [@thePorenta](https://github.com/theporenta).
It lives inside of PowerPoint itself and usage should be self-explainatory.

The Android App was written independantly from this server. Only the protocol had been agreed upon.

[**Download**](https://github.com/sgade/powerpoint-remote-server/releases)

# How to use

1. Install the AddIn
2. Click the "*Start*" button.
3. On your Android device, start the app and wait for the server to be discovered.
4. Connect to your PowerPoint instance and enter the pairing code displayed in the PowerPoint ribbon UI.
5. **Remote control your slides.**

# Supported versions

This AddIn has been developed with [Microsoft Office PowerPoint](http://office.microsoft.com/de-de/powerpoint/) 2007 as a testing platform.
To make this run in VS2012+ and still use PowerPoint '07, I did a [change to the project file](http://stackoverflow.com/questions/12277023/how-can-i-create-a-vsto-office-2007-add-in-using-vs-2012) which can be found [here](https://github.com/sgade/powerpoint-remote-server/commit/be3c70f451f73b22be78c5df05b17d96cfa5ff3c#diff-31a00a9f0021feabd4845a1614e33f65R218).
