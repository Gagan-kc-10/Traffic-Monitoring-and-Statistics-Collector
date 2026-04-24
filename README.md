# SDN Traffic Monitoring using Ryu

#Description
This project implements a traffic monitoring module using the Ryu SDN controller. It collects flow statistics such as packet count and byte count from OpenFlow switches.

#Features
- Learning switch implementation
- Flow rule installation
- Traffic monitoring every 5 seconds
- Displays packet and byte statistics

#Technologies Used
- Python
- Ryu Controller
- OpenFlow 1.3
- Mininet

#How to Run
1. Start Ryu controller:
   ryu-manager traffic_monitor.py

2. Run Mininet:
   sudo mn --topo single,2 --controller remote
   
3. Ping:
   h1 ping -c 10 h2

#Output
Shows flow statistics including:
- Packet count
- Byte count
- Total traffic

#Screenshots

Traffic Statistics Output
![Output](screenshots/output.png)

Mininet
![Mininet](screenshots/mininet.png)
