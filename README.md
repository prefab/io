This repository includes the code I've used to redirect mouse clicks and key presses to applications. It also includes the low-level methods for capturing pixels from a window.

To get started, load the PrefabVideoCapture.csproj project. If you run this, it will launch a small application that allows you to record video footage from a window. Click "Select a Window" and click on the window you'd like to record.

The best way to see what's going on underneath the hood is to look in the [CaptureThread](CaptureThread.cs) file, which runs a loop that captures pixels and stores them into an AVI stream.