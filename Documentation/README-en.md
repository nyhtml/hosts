# Hosts
The computer file [host](https://github.com/nyhtml/hosts/tree/master/hosts) is a plain operating system text file that maps hostnames to IP addresses.

## Table of Contents

* [AdAway version 5.4.0 (50400)](#adaway)
* [DNS66 version 0.6.8 (29)](#dns66)
* [DNSNet version 1.34 (63)](#dnsnet)
* [Disclaimer](#disclaimer)

### AdAway
A Free and Open Source ad blocker for Android.

The application is available for rooted and non-rooted devices.
Using rooted device, the application update your system hosts file that contains a list of mappings between host names and IP addresses.
Using non-rooted device, the application use the VPN feature to block outgoing connections to ads and trackers.
So when an app requests an ad or a tracker from a host in that file, this request is redirected to the local IP 127.0.0.1, which does nothing.

You can download predefined ads and blocker lists as hosts files from within the app to incorporate. It is also possible to use your own files and to add certain hosts to allowed and blocked lists.
There are options to run a local web server to respond to blocked host names and to direct requests to the IP address of your choosing instead.

### DNS66
DNS66 allows blocking host names via DNS. This can be used for ad blocking. It
also allows other DNS servers to be added, for more privacy.

Compared to AdBlock Plus, this works without proxy stuff; and it also does not
require root, like AdAway does: DNS66 establishes a VPN interface, and redirects
DNS server traffic to it. The VPN interface filters the traffic, only allowing
queries for hosts that are not blacklisted.

A host (list) can be configured as allow, deny, or ignore. A later entry in the
list overrides a previous entry.

Custom DNS Servers can be configured as well, using the same UI, but no
differentiation is made between ignored and denied servers.

### DNSNet
DNSNet allows you to take more control over what internet traffic goes in and out of your device. You can download host files to block a set of known advertising or malicious host names and then create exemptions where you see fit.

It works by creating a lightweight VPN service that filters your internet traffic as you use your device. If you ever have trouble with connecting to a site or using an app, you can always exempt an app from filtering or create an exception for a specific host name.

#### Disclaimer:
Rooting your device (to use AdAway) may void its warranty!!!
