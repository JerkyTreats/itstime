# ITSTIME

![20250617_1258_It's Time Alerts_storyboard_01jxzqhzr7ew5sab1jta4ba8sk (2)](https://github.com/user-attachments/assets/751b4e24-e4e5-4053-af60-db90ef02bab5)

_Apologies for the jank video I wanted to try it out_

Its a video to be played of a startup's landing page, for "ITSTIME".

A mobile notification is zoomed in from ITSTIME, saying: It's time to **take your Vitamin D**. 

Camera focus shifts down, showing a carousel a series of `It's time to...` notifications: 

*  Plan your day
* Join a video call in 15 minutes
* Record how well you slept

Then spinning through dozens more too fast to see. 

Fade to white: ITSTIME branded logo 

## Description of Product 

A dead simple mobile app that's literally just push notifications. 

Then build some schedulizer backend. Just throw it in the tailscale network for now. 

I think we'll probably want to have a register/ endpoint, so the API Mesh can send it commands. Geez I wonder if it really is time to consider gRPC contract standards- protobufs? 

But obviously it will have a bunch of self defined scheduled reminders to ping about. So mesh integration can be for later. 
