# Grabify Domain Hosts
This repository contains a hostfile-style listing of Grabify domains, and is automatically updated daily. 

## Installation
To use this file, go to hosts.txt in this repo, and open the Raw version. Then, take the contents and do one of the following below.

### Method 1: Systemwide
This hosts file can be installed to block Grabify domains systemwide. Where you need to copy and paste the contents of hosts.txt depends on your OS. If you want an OS-agnostic approach, see Method 2.

Copy the contents to the bottom of your hosts file. On Windows, this will be in C:\Windows\system32\drivers\etc\hosts, on Linux, it will be in /etc/hosts

Once added, this will block all Grabify links systemwide.

### Method 2: Browser Blocking
TODO

## Warning about DNS Over HTTPS
If your browser is configured to use DNS over HTTPS(DoH) then this will not block requests in your browser. You will either need to disable DNS over HTTPS in your browser, or use Method 2 to block the domains using uBlock Origin.
