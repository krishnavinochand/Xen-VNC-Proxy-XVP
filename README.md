# Xen-VNC-Proxy-XVP

One of the most common requests from XenServer customers is for a web interface, so that they can manage their VMs from a browser. I’m pleased to say that I’ve found one!
It’s called xvp, and has been developed by Colin Dean at Durham University in the UK. There are four components:
•    xvpweb: A web front end for XenServer, running on Apache/PHP.
•    xvpviewer: A Java applet for accessing XenServer consoles (used by xvpweb, of course).
•    xvp: A server-side proxy for XenServer consoles, so that you can use ordinary VNC clients.
•    xvpdiscover: A tool that queries a XenServer pool, and writes the appropriate configuration files for xvp and xvpweb.
