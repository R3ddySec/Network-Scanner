Usage
Clone the Repository
Use the following command to clone the tool to your local machine:

bash
Copy code
git clone https://github.com/R3ddySec/networkscanner.git  
cd networkscanner  
Run the Tool
Make sure you have Python installed on your system (Python 3.6 or above).

1. Discover Devices on the Network
To find all active devices in a given network range:

bash
Copy code
python network_scanner.py  
Select option 1 and input the network range (e.g., 192.168.1.0/24):

go
Copy code
Enter network range (e.g., 192.168.1.0/24): 192.168.1.0/24  
2. Scan a Device for Open Ports
To scan a specific IP address for open ports:

bash
Copy code
python network_scanner.py  
Select option 2 and input the target IP address (e.g., 192.168.1.10):

css
Copy code
Enter the IP address to scan: 192.168.1.10  
Modify Scanning Range
The tool scans ports from 1 to 1024 by default. You can edit the script to scan additional ports by modifying the range in the scan_ports function:

python
Copy code
for port in range(1, 65536):  # Scans all 65535 ports  
Feel free to paste this into your GitHub repository's README or documentation! Let me know if you need further adjustments.
