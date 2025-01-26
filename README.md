# Octo-related-logs
Logs to help figure out why OctoEverwhere blocked uploads form all three slicers.
 502 Gateway error after installing OctoEverywhere

I am running Klipper on a BTT Pad 7. I installed OctoEverywhere yesterday, and in the 1st print that I have tried since installing it I am getting the 502 Gateway error. I have rebooted the machines, done a firmware restart, the file itself is tiny, barely 1 MB. I have changed the address of my printer in Orca to the shared connection link from OctoEverywhere.

The main difference between directly pointing to the IP address and the shared connection link is the file appears to upload completely with the shared connection (shows 100%), but then after a pause I get the 502 error again.

I can access the printer through mainsail both from a web browser and within the device tab of Orca slicer itself. So I'm able to connect easily to the printer and do all the other stuff I normally could do in mainsail, I just can't upload a file for printing.

So, 2 questions:

1.    I've seen the 502 error pop-up with Orca slicer before and it appears it may be a memory issue, but that is clearly not the case for a 1 MB file when I have 25 gigs available on the SD card. This appears to be a configuration issue either with Klipper or with Orca after the Octo install. Does anyone have any clue on what I should be looking for how to address this? I am by no means a Linux/Python expert.

2.    Keeping in mind I am not a Linux expert, how can I completely remove the OctoEverywhere installation? Would the easiest answer be to do a factory reset, re-update everything, and then reinstall my backed up configuration files?

2 further observations:

1.    I was able to confirm this is NOT an Orca issue. Both Prusa and Cura slicers lost the ability to upload prints to the printer as well.

2.    After uninstall and a few restarts, I now can send files to print as normal. So, this is 100% an OctoEverywhere issue.

