# LeaderApp
This application is to be used in conjunction with the Follower application. This is the primary means for a Leader to communicate with the Follower. It is supported on MacOS and Windows. We will also be using the HoloLens2 Portal to access the live video feedback from the HoloLens2 front camera. 

## Instruction to Load the Unity Application
1) Download this repository and open it in Unity version 2022.3.15f1
2) Make sure that you enable Unity to use your computer microphone.
3) Click Play on Unity windows.
4) This should allow the follower to send and receive voice calls in real-time with the other party.

## Instruction to Access Live Video
1) Enable the Developer setting on the HoloLens2 by going to Settings>Updates>For Developer>Toggle Button to Enable Developer Mode.
2) Get the IP Address of the HoloLens2 by going to Settings>Network&Internet>Select the network you are connected to>Advance Setting>Get the iPv4 address
3) On a web browser go to https://[iPv4]. There will be a warning that it is unsafe but just click Proceed with unsafe.
4) Enter login information set up for your Hololens portal. Now, you have access to the HoloLens Portal.
5) On the Hololens Portal navigate to View> Mixed Reality Capture> Start Live Preview. Set the live preview quality to Low (240p, 15fps, 0.6MBits) so that the latency is not so bad. If the video stops playing just stop the live preview and start it again.


