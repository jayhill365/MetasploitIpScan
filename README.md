# MetasploitIpScan
Metasploit script that can be used to scan an IP address for potential vulnerabilities

This script will perform a TCP port scan on the specified IP address, using the specified number of threads and port range. It will then run a directory scanner to search for hidden directories and files, a HTTP version scanner to identify the version of HTTP in use, an SSL enumeration scanner to identify SSL certificates and configurations, a server header scanner to identify the server type and version, and a Domino enumeration scanner to gather information about a Domino server.

After running these scans, the script will list any potential vulnerabilities that were identified. It is important to note that this script is just a starting point, and you may need to adjust or add additional scans and options depending on your specific needs and requirements.
