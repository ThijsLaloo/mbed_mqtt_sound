# Mbed MQTT sounds
The purpose of this exercise is to publish some frequencies to a mqtt channel.
The Mbed subscribes to the same channel. The frequencies received are put in a mailer. The Mbed will play the sound for some seconds and thereafter pick the next frequency from the mailer and so on till there are no frequencies left in the mailer.

## Installation
1) You need to add HelloMQTT to your compiler from: https://os.mbed.com/teams/mqtt/code/HelloMQTT/
2) Replace the main.cpp code with the code found in this repository
3) compile and put on the Mbed
4) Happy testing


## Usage example
1) Install the MQTT-box plugin from chrome.
2) plug in the power to the Mbed
3) publish for example '2000' in MQTT-box.
4) The Mbed should play the sound with frequency 2000Hz for some seconds.