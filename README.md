# Network-Attack-Analysis

The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, an automated alert from the monitoring system indicated a problem with the web server. Attempting to visit the company’s website resulted in a connection timeout error message.

A packet sniffer was used to capture data packets in transit to and from the web server. A large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. It is suspected that the server is under attack by a malicious actor. 

The server is taken offline temporarily so that the machine can recover and return to a normal operating status. Configuration of the company’s firewall to block the IP address that was sending the abnormal number of SYN requests was implemented. The IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. The manager needs to be alerted about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. The boss needs to be briefed about the type of attack discovered and how it was affecting the web server and employees.
