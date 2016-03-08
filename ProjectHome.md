**Development has stopped. Support for this script has come to a halt. if you wish to make changes to this program feel free to let know and I will give you the ability to upload. Feel free to continue to post bug reports however they will be ignored (by me) for the time being - (might still be useful to those wishing to continue development).**

Interrupting wireless communications is, in some areas, illegal. Use at your own risk.

This is a script i wrote to scan on the user specified channel, and then constantly sends out de-authenticate packets to all access points that channel. This is a bash script and being such you cant expect it to remain stable for more than a few hours. Like my other project autocrack; this will attempt to automatically detect your wifi card, and use it if you don't specify one at the command line. You will need the aircrack-ng suit for this to work.

This will work on Ubuntu 8.04 - 10.04 LTS (untested on newer ubuntu releases). Should work in backtrack 3/4/5 aswell.

To close down this program you will have to manually ctrl-c it all. You will also have to disable monitor mode by either using autocrack (./autocrack.sh removemon) or with aircrack (airmon-ng stop WIFICARD)