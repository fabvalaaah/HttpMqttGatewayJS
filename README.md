# HttpMqttGatewayJS
NodeJS HTTP to MQTT unidirectional gateway.

This is a NodeJS NetBeans project, tested with NodeJS v8.10.0 and Mosquitto (a
MQTT protocol implementation from the Eclipse Foundation) on Ubuntu Linux
16.04.3 LTS x64.

This piece of software listens to messages coming from a local HTTP port and
forwards everything it reads from it to an MQTT broker (on a dedicated output
channel).

## Installation
Run `npm install` to install the dependencies of the project.

## Setup
Gateway properties are set in the JSON file "setup.json".

## Usage
Run `npm start` to launch the gateway on the local machine.

DONATION:
As I share these sources for commercial use too, maybe you could consider
sending me a reward (even a tiny one) to my Ethereum wallet at the address
0x1fEaa1E88203cc13ffE9BAe434385350bBf10868
If so, I would be forever grateful to you and motivated to keep up the good work
for sure :oD Thanks in advance !

FEEDBACK:
You like my work? It helps you? You plan to use/reuse/transform it? You have
suggestions or questions about it? Just want to say "hi"? Let me know your
feedbacks by mail to the address fabvalaaah@laposte.net

DISCLAIMER:
I am not responsible in any way of any consequence of the usage of this piece of
software. You are warned, use it at your own risks.