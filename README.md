# splunk-ip-info-dashboard
Splunk dashboard designed to display and visualize ip traffic coming into a network

The project's directory system is as follows:

splunk-ip-info-dashboard/
|--README.md
|--allTraffic.spl <--- Nothing special here. Just a map with all the iplocatin data splunk has to make sure it's working correctly
|--firewallTraffic/
|  |__ inboundTraffic.spl <--- The table with the actual data
|  |__ inboundTrafficMap.spl <--- Map representation of data
|  |__ inboundTrafficMap.png <--- Just a visualization of what the map might look like
|--DNS/
|  |__ DNSLookup.spl
|  |__ DNSLookupMap.spl
|  |__ DNSLookupMap.png
|--blocked/
|  |__blockedIPS.spl
|  |__blockedIPSMap.spl
|  |__blockedIPSMap.spl
|--scanning/
   |__webCrawlerDetector.spl <--- Very low tech solution to finding out if a domain name is on a list of common crawlers + a few handy keywords which categorize chances of scanning

## firewallTraffic
