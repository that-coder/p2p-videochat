# p2p-videochat

A simple peer to peer video chat communication using WebRTC.

To start the application,
Run npm install on the project directory
Run the below commands to install app dependencies.

```
npm install simple-peer -g 
npm start
```

The application will run on port 9696 by default, so open the browser and hit the URL http://localhost:9966/.

## Steps to start video chat using p2p

1. Open two tabs in chrome and run http://localhost:9966/#start on the first tab and http://localhost:9966 on the second.
2. Allow camera and microphone permissions on the browser.
3. "Your_ID" will be generated in the input box of the first tab, copy and paste it on the second tabs "other_id" field.
click on the connect button in second tab. This time id for the second tab will be generated and do the same procedure in first tab.
