Radio-Browser
=============

GTK3+ port from original source https://github.com/segler-alex/rhythmbox-radio-browser/issues
for Rhythmbox 2.96


 - http://askubuntu.com/questions/210688/how-to-integrate-rhythmbox-to-play-internet-radio/210726#210726

![pic](http://i.stack.imgur.com/txTPz.png)

[![Flattr Button](http://api.flattr.com/button/button-static-50x60.png "Flattr This!")](https://flattr.com/thing/1237090/fossfreedomradio-browser-on-GitHub "Rhythmbox Radio Browser")


Installation
------------

<pre>
git clone https://github.com/fossfreedom/radio-browser
cd radio-browser
./install.sh
</pre>

For a system wide install then:

<pre>
git clone https://github.com/fossfreedom/radio-browser
cd radio-browser
sudo make install
</pre>

Then launch rhythmbox and enable the plugin "Internet Radio Browser"

Non-Debian based distros
------------------------

You will need to install the equivalent packages for your distro: `streamripper gir1.2-gconf-2.0`

Debian & Ubuntu 12.04 notes:
-------------------

packages required to be installed:

    sudo apt-get install streamripper gir1.2-gconf-2.0

This is packaged in my PPA:

    sudo add-apt-repository ppa:fossfreedom/rhythmbox-plugins
    sudo apt-get update
    sudo apt-get install rhythmbox-plugin-radio-browser
