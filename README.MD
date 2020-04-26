Three scripts that scan globally for vulnerable memcached, NTP or OpenDNS servers. The script then strips the scan results to only IPs before running the list through Nmap to check a pre selected vulnerability against the hosts. All vulnerable servers are then saved to their appropriately labeled text files by server type within the program's directory.

<h1> Installation </h1>
Install the folder "Bot-Lab" in the root directory and then run "chmod +x install" followed by "./install"
usage example: ./NTPScan
