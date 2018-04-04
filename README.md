# problemsforfutureme
Record and send dictations easily

## Low effort dictations
You have trouble sleeping and your mind races, thinking about TODOs, problems, ideas and random anxieties? But writing them down would require either paper,pen(+light) or getting your mobile phone, which also produces waking light and typing wakes you up even more?
Since it's night, it's silent, so a microphone for quiet dictations could be a solution for you. And since your bed it mostly in one place, multiple buttons (or optional voice activation?) can make it easy to just record something, press once to record, press twice to end. Your recording get's send via email to you, ready in the morning, and hopefully enough for your brain to let go of the issue for tonight...

## Hardware
- Computer (Raspberry Pi, anything Linux and always-on)
- Microphone (USB for RPi, but anything connected to the computer)
- Buttons (via GPIO for RPi, but anything producing software events)

## Software
- This script running
- Login to a mailserver for sending dictations

## Dependencies
- python3
- smtplib

## Okay, Google?
Sure, you could use voice activated services like Alexa, Siri or Google.
But those pose legitimate privacy threads and your nightly dications (and any other sound you make anytime) will be sent to Apple/Google/Amazon/Microsoft.
If you don't want a microphone listening to everything you say, this project could be a good alternative. It does not send your audio to Google, but you don't just need to trust my word on that, since the code is small enough to quickly check that it doesn't ;)
