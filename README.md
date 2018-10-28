Why Chattervedi?
It's 2018, WebRTC is natively supported in all desktop & mobile browsers but still, most major players (Hangouts, Skype, Appear.in etc) ask you to download their app to use the service.

Chattervedi
Chattervedi is a video chat app that works in most major desktop & mobile browsers. No Signup. No Downloads. Just video chat.

Chattervedi uses WeBRTC for video communication and a socket.io 
server that serves as a signaling server. It uses WebRTC mesh when more people 
is added to the call, it means each video stream in a group call is a separate P2P connection. 
There is no hard limit on the number of people in the group video call, but the quality of 
the call will decrease when more than 5 people join the call.

Credits:
https://github.com/anoek/webrtc-group-chat-example

If you are here for checking the p2p video call w/o signaling server, head over to the gh-pages branch. 
And check out the demo here chattervedi.tk
