# node-red-contrib-ai-function
A <a href="http://nodered.org" target="_new">Node-RED</a> node to call ai function of watson machine learing.

## Install

Run the following command in the root directory of your Node-RED install or home directory (usually ~/.node-red) and will also install needed libraries.

        npm install node-red-contrib-ai-function

### Runtime information
This node was tested to Node.js v8.3 and NPM 5.6.0 on Node-Red v0.19.3 

## Usage

sample msg.payload is as follows:

```
msg.payload = {
    "fields": ["CLASS", "AGE", "BP", "AL", "SC", "POT", "PCV"],
    "values": [[null, 75, 70, 0, 0.8, 3.5, 46]]
}
``` 