
# Grabify Domain Hosts
This repository contains a hostfile-style listing of Grabify domains, and is automatically updated daily. 

## Installation
To use this file, go to hosts.txt in this repo, and open the Raw version. Then, take the contents and do one of the following below.

### Method 1: Systemwide
This hosts file can be installed to block Grabify domains systemwide. Where you need to copy and paste the contents of hosts.txt depends on your OS. If you want an OS-agnostic approach, see Method 2.

Copy the contents to the bottom of your hosts file. On Windows, this will be in C:\Windows\system32\drivers\etc\hosts, on Linux, it will be in /etc/hosts

Once added, this will block all Grabify links systemwide.

### Method 2: Browser Blocking (Auto-updating)
For this method, you will need uBlock Origin (or a derivative like AdNauseum) for [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=homepage-collection-featured). Once the uBlock icon is in your browser's taskbar, click it, and click the settings icon that looks like a set of cogs. In the **Filter Lists** tab, you will see a number of pre-made lists of things to block. In this case, we want to scroll all the way down to **Custom**, then tick the **Import** box. You will be presented with a textbox to enter a list of links. Paste in https://raw.githubusercontent.com/NGGJamie/Grabify-Domain-Hosts/main/domains.txt

After you've pasted in the link, scroll up and click **Apply Changes** at the top of the screen. Now when you try to go to any Grabify webpage, uBlock Origin will block your browser from completing the request.

## Warning about DNS Over HTTPS
If your browser is configured to use DNS over HTTPS(DoH) then this will not block requests in your browser. You will either need to disable DNS over HTTPS in your browser, or use **Method 2** to block the domains using uBlock Origin.

