# OFDL
Onlyfans media downloader with graphical user interface using Python's tkinter.

Downloads media files from Onlyfans (images, videos, highlights)

On Windows the only requirement should be requests which can be installed using pip.exe in the Scripts folder of the python installation directory - "pip install requests". 


Before logging in, press F12 (or inspect/inspect element and go to the network tab) to bring up the "developer tools" and then log in. Type "init?" in the search bar and retrieve the "sess" cookie from the header section. Copy the sess cookie starting after the equal "=" to, but not including the semi-colon ";". Also copy the user-agent:

<img src="https://github.com/Hashirama/OFDL/blob/master/onlyfans1.png">

Paste the sess cookie and user-agent to the application and press OK:

<img src="https://github.com/Hashirama/OFDL/blob/master/onlyfans2.png" width="500">


 It should then retrieve the users you're subscribed to. 
 
 # Requirements

Written using Python 3.7 so use 3.7 or anything above.

On Windows, tkinter should already come with Python 3 so the only thing needed would be requests:

<pre><code>pip install requests</code></pre>

Then run the script OFDL.py by double clicking it or from IDLE (IDLE would be better just incase any errors occur).

I don't believe tkinter comes installed with Python 3 on Ubuntu so it can be installed using:

<pre><code>sudo apt-get install python3.7-tk</pre></code>

(Assuming you are using Python 3.7.) If requests is needed run:

<pre><code>pip3 install requests</code></pre>

To run script: <pre><code>python3.7 OFDL.py</code></pre>

# Note

I didn't implement stories because I don't have any user to test the functionality on but I've implemented Highlights.