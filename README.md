# Wi-Fi Traffic Analyzer

Analyze Wi-Fi network traffic using **Splunk**, including protocol trends, traffic distribution, and packet analysis.

---

## Dashboard Overview

This project visualizes Wi-Fi network traffic captured via Wireshark and imported into Splunk. The dashboard includes:

1. **Protocol Trend Over Time** – Shows how different protocols are used over time.  
2. **Unusual Protocols** – Highlights rarely used protocols.  
3. **Peak Traffic Hours** – Identifies periods of high network activity.  
4. **ARP Request/Reply Ratio** – Monitors ARP traffic for anomalies.  
5. **Packet Size Over Time** – Visualizes packet size distribution over time.  
6. **Packet Count by Minute per Protocol** – Counts packets per minute, separated by protocol.  
7. **Top Destination Devices** – Shows devices receiving the most traffic.  
8. **Packet Size Distribution** – Shows distribution of packet sizes in the network.  
9. **Traffic Over Time** – General traffic trends over time.  
10. **Protocol Distribution** – Breakdown of traffic by protocol.

---

## Screenshots

### Trafic Over Time & Traffic Analysis
<img width="1912" height="1075" alt="Screenshot 1" src="https://github.com/user-attachments/assets/cea890d9-3a48-4ac1-8064-b7cf8d48332b" />

### Top Destination Devices & Packet Count by minute per protocol
<img width="1912" height="1075" alt="Screenshot 2" src="https://github.com/user-attachments/assets/336b3b6f-9ef9-4d57-8d6f-8d33204c841f" />

### Packet Size & Peak Traffic Hours
<img width="1913" height="1076" alt="Screenshot 2025-11-25 115037" src="https://github.com/user-attachments/assets/4bd89cd4-a54f-4284-acf8-aca742d6a7aa" />

### Protocol Trend & ARP Request/Reply Ratio
<img width="1917" height="1077" alt="Screenshot 4" src="https://github.com/user-attachments/assets/54778e55-1386-4dc4-8944-63646f3fedfd" />

## Project Structure

```
wifi-traffic-analyzer/
├── README.md            # Project description and dashboard documentation
├── screenshots/         # Screenshots of Splunk dashboard panels
├── network_logs.csv     # CSV data for network logs and queries
└── dashboards/          # Optional: exported dashboard XML/JSON
    └── my_dashboard.xml
```

## Usage

1. Open **Splunk** and create a new dashboard.  
2. Import `network_logs.csv` into Splunk as a data source.  
3. Recreate panels using the queries provided in the `network_logs.csv` data.  
4. (Optional) Import exported dashboard XML from `dashboards/` folder.  

---

## Author

**TahsinAhmedRifat**  
- Email: rifat3387b@gmail.com  
- GitHub: [https://github.com/TahsinAhmedRifat](https://github.com/TahsinAhmedRifat)
