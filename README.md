# Port-scan-using-Python
Python-based port scanner that identifies open ports on a target machine. This project helps to understand network scanning, socket programming, and multithreading for efficient scanning.
Target Input: The user enters the target IP address and the range of ports to scan.
Socket Connection: The script attempts to establish a connection to each port.
Service Identification: If a port is open, the scanner tries to identify the running service.
Banner Grabbing: The scanner retrieves any available banner information from the open port.
Multithreading for Speed: The scanning process is optimized using Python’s ThreadPoolExecutor, allowing concurrent scanning of multiple ports for faster results. 
Formatted Output: The results are displayed in a structured table, highlighting open ports, detected services, and banners.
