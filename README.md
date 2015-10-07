# System Setup

This is just a quick and easy place for me to store my server setup procedures.  

To be run on a basic Debian 8 Netinst, installed with SSH server and nothing else.

Highly recommended to be running grsecurity (I'm using grsec3.1-test, on kernel 4.1.7)

Features:
* Secure SSH configuration
* Hardened Kernel settings
* Download and extract the latest version of Lynis
* Pre-emptively implements some of Lynis' security recommendations
* Installs and configures Tripwire & Tiger
* Also includes my public SSH key, so make sure you remove that if you're not me

Please feel free to use it.  Pull requests are welcome.
