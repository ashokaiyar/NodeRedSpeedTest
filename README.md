This is my version of an Internet Speedtest flow. It is based on previous flows by <a href="https://flows.nodered.org/flow/b79e4d9cfc4b474b9975a8bb3b80fb64" target="_blank">bloigge</a> and <a href="https://flows.nodered.org/flow/e3e8c7f4807f383ab85d61ff2dfda208" target="_blank">DeepPurple77</a>.

My version differs from theirs in the following ways:

1. I make use of <a href="https://flows.nodered.org/user/steffen" target="_blank">steffen's</a> <a href="https://flows.nodered.org/node/node-red-contrib-speedtest" target="_blank">node-red-contrib-speedtest</a>, so there is no need to install the command-line speedtest client.
2. Output from the node is stored as flow variables, and I use these variables to repopulate the SpeedTest Dashboard when Node-RED is restarted.
3. Clicking on the name of the speedtest server will open a new browser window linked to the results from Ookla.

Flow Diagram:

<img src="https://raw.githubusercontent.com/ashokaiyar/NodeRedSpeedTest/main/Screen%20Shot%202022-07-25%20at%2011.58.49.png" alt="SpeedTest Flow" style="width:500px;height:232px;">

Dashboard:

<img src="https://raw.githubusercontent.com/ashokaiyar/NodeRedSpeedTest/main/Screen%20Shot%202022-07-25%20at%2011.27.56.png" alt="SpeedTest Dashboard" style="width:500px;height:333px;">
