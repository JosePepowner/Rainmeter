# Rainmeter
Modified Rainmeter skin https://www.deviantart.com/mekurukitoxd/art/HOXY-2-Rainmeter-Skins-System-monitoring-803532685. <br>
Just a basic dump of the modified skin. For both myself to reference back to and others if they need an example. <br>
I take 0 credit in creating the skin and full credit goes to the original artist. I just made it work for me. <br>
I modified some skins (images) and some values to better suit what I wanted.<br>
<h1>1.1.1 Changes</h1>
<h2>GPU:</h2>
Reworked Skin to properly display RPM on the fan. See notes for info.
<h1>1.1 Changes</h1>
<h2>GPU:</h2>
Complete rework of the GPU.ini file. Instead of pointing to MSI afterburner I've completely moved the pointers to HWInfo. This was done for compatability as well as keeping less programs open.
<h1>1.0.1 Changes</h1>
<h2>CPU:</h2>
Removed an extra line left in during testing. Line 211.
<h1>1.0 Changes</h1>
<h2>CPU:</h2>
<ul>
    <li>Now supports HWINFO instead of CoreTemp. (Indexing method)</li>
    <li>Now monitors 8 cores.</li>
    <li>Now monitors the fan.</li>
    <li>Image was modified to support more values.</li>
    <li>Values were modified for better spacing to accommodate new values.</li>
    <li>Modified bits of the values to rely more on either HWINFO or MSIAfterburner.</li>
    <ul><li>No real noticeable difference, just a me thing.</li></ul>
    <li>Update rate changed to 5s.</li>
</ul>
<h2>GPU:</h2>
<ul>
    <li>Modified bits of the values to rely more heavily on MSIAfterburner.</li>
    <ul><li>No real noticeable difference, just a me thing.</li></ul>
    <li>Update rate changed to 5s.</li>
</ul>
<h2>Network:</h2>
<ul>
    <li>Fixed to display in seconds. It was displaying the half .5 speed.</li>
</ul>
<h2>Time:</h2>
<ul>
    <li>Changed to display a 12 hour clock instead of 24.</li>
    <li>Changed the separator line to display "/" instead of "-" for date.</li>
    <li>Changed the date format to MM-DD-YYYY.</li>
</ul>
<h2>Uptime:</h2>
<ul>
    <li>Changed to display current session. Was tracking the overall PC session.</li>
</ul>
<h2>Drives:</h2>
<ul>
    <li>Update rate changed to 30min.</li>
</ul>
<h2>Recycle:</h2>
<ul>
    <li>Update rate changed to 30min.</li>
</ul>
<h2>Sound:</h2>
<ul>
    <li>Update rate changed to 5s.</li>
</ul>
<h2>General / Overall:</h2>
<ul>
    <li>Added a few string separators. Example CPU name now displays just the CPU name not the socket it's in.</li>
    <li>Modified other strings to fix certain sections from displaying the "%" wrong.</li>
</ul>

<h3>Notes</h3>
You must change the values within the CPU file and Network file.<br>
Within CPU ini / GPU ini change the value CPURPM / GPURPM within the variables section to match your RPM.<br>
Within Network ini change the value maxDownloads / maxUploads within the variables section to match your Mbs.<br>
Lastly because of HWinfo and the way it interacts with the values you must follow this guide to set up your CPU properly. https://docs.rainmeter.net/tips/hwinfo/ <br>
Essentially my CPU values will not work for sensors as they might be labeled differently, have more values in general, or be in a completely different order than yours. <br>

<h3>Close</h3>
Please understand I am not great at all this and did this for myself. So if things are broken I encourage you to let me know but please understand I may not bother fixing them. 



