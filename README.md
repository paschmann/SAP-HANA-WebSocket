SAP-HANA-WebSocket
==================

A small hack for SAP HANA to repurpose the Debugging.xsws file for websocket use (could be data retrieval or any other server side functionality).

Read more about this here: [http://scn.sap.com/community/developer-center/hana/blog/2014/07/25/sap-hana-websockets]("http://scn.sap.com/community/developer-center/hana/blog/2014/07/25/sap-hana-websockets")

### Install

1.) Using the Web IDE, open SAP -> HANA -> XS -> Debugger

2.) Make a backup of the Debugger.xsws file or simply comment out the contents.

3.) Paste the code into the file from Github

4.) Create the Websocket.html file and paste the contents of the Github file

5.) Create the app.js file and paste the contents of the Github file

6.) Open the Websocket.html file and enter any SQL statement

(Be sure you have the debugger security role)
