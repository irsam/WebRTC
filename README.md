# WebRTC. Video-conferenc
This sample code from @https://github.com/lucaslouca/ for demonstrates a client/server architecture running on <a href="https://nodejs.org" target="_blank">Node.js</a>, that enables users to setup up a video conference. The app makes use of <a href="http://socket.io" target="_blank">Socket.IO</a> and <a href="http://www.webrtc.org" target="_blank">WebRTC</a>.

When a peer visits <a href="http://127.0.0.1:1337/" target="_blank">http://127.0.0.1:1337/</a>, a new room url is generated, which can then be used to invite others to the video conference.

At the moment WebRTC is supported only by a limited number of browsers: Chrome, Firefox and Opera.

## How to run the code
1. Clone the repo
2. `$ cd into the folder `
3. `$ npm install` (you may need root access)
4. `$ node server.js`
5. Access the app from a WebRTC capable webbrowser
