## Simple-android-chat-with-SignalR

To communicate the android app with SignalR Server you must do these steps below: 

1. Deploy SignalR Server to local iis
2. Go to SignalRService class in android project, find String serverUrl = "http://192.168.0.104/" and change to your IP address
3. Run your project and everything should work
