# asighnment_7

PORT SCANNER
The script performs a simple TCP port scan by attempting to establish a connection to each port within the specified range on the target IP address. If the connection is successful (result is 0), it means the port is open, and the port number is added to the open_ports list. If the connection fails (result is not 0), the port is considered closed, and the port number is added to the closed_ports list.

NETWORK SECURITY
The script uses nmap to perform the port scans and extracts the open ports from the command output. It then calculates the network security score based on the number of open TCP and UDP ports. The score is decremented for each open port found.
