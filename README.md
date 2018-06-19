# p2p-videochat

This is a simple application explain how simple peer to peer video chat communication is working using WebRTC.
To run the application,

Run npm install on the project directory, after that run the below commands to install app dependencies.

```
npm install simple-peer -g 
npm start
```

The application will run on port 9696 by default, so open the browser and hit the URL http://localhost:9966/.

## Steps to start video chat using p2p

1. Open two tabs in chrome and run http://localhost:9966/#start on first tab and http://localhost:9966 on the second one.
2. Allow camera and microphone
3. "Your_ID" will be generated in the input box of the first tab, copy and paste it on the second tabs "other_id" field.
click on the connect button in second tab. This time id for the second tab will be generated and do the same procedure in first tab.
