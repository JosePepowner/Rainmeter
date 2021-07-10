# Rainmeter
Modified Rainmeter skin https://www.deviantart.com/mekurukitoxd/art/HOXY-2-Rainmeter-Skins-System-monitoring-803532685
Just a basic dump of the modified skin. For both myself to reference back to and others if they need an example.
I take 0 credit in creating the skin and full credit goes to the original artist. I just made it work for me. 
I modified some skins (images) and some values to better suit what I wanted. 

1.0 Changes
CPU:
Now supports HWINFO instead of CoreTemp. (Indexing method)
Now monitors 8 cores.
Now monitors the fan.
Image was modified to support more values.
Values were modified for better spacing to accommodate new values.
Modified bits of the values to rely more on either HWINFO or MSIAfterburner. 
Update rate changed to 5s.
GPU:
Modified bits of the values to rely more heavily on MSIAfterburner.
    No real noticeable difference, just a me thing. 
Update rate changed to 5s.
Network:
Fixed to display in seconds. It was displaying the half .5 speed.
Time:
Changed to display a 12 hour clock instead of 24.
Changed the separator line to display "/" instead of "-".
Uptime:
Changed to display current session. Was tracking the overall section. 
Drives:
Update rate changed to 30min.
Recycle:
Update rate changed to 30min.
Sound:
Update rate changed to 5s. 

General / Overall:
Added a few string separators. Example CPU name now displays just the CPU name not the socket it's in. 
Modified other strings to fix certain sections from displaying the "%" wrong. 
