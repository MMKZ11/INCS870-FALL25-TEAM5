CICIoT 2023 dataset link below

https://www.unb.ca/cic/datasets/iotdataset-2023.html

This project uses a **10-class subset** of the CICIoT2023 dataset
(PCAP CSV files).  
The raw CSV files are **not included** in this repository due to size
and license restrictions.

---

## 1. Source dataset

Official dataset page (CICIoT2023):

- https://www.unb.ca/cic/datasets/iotdataset-2023.html

Please follow the instructions on the official website to request and
download the data.

---

## 2. Classes used in this project

From the full CICIoT2023 dataset, we only use the following **10 classes**:

| Class label            | # CSVs used | Example file(s)                                         |
|------------------------|------------:|---------------------------------------------------------|
| `Benign_final`         | 2           | `BenignTraffic1.pcap.csv`, `BenignTraffic3.pcap.csv`    |
| `BrowserHijacking`     | 1           | `BrowserHijacking.pcap.csv`                             |
| `DDoS_HTTP`            | 1           | `DDoS-HTTP_Flood-.pcap.csv`                             |
| `DDoS_ICMP`            | 2           | `DDoS-ICMP_Flood.pcap.csv`, `DDoS-ICMP_Flood1.pcap.csv` |
| `DDoS_SYN`             | 2           | `DDoS-SYN_Flood.pcap.csv`, `DDoS-SYN_Flood1.pcap.csv`   |
| `DDoS_TCP`             | 2           | `DDoS-TCP_Flood.pcap.csv`, `DDoS-TCP_Flood1.pcap.csv`   |
| `DDoS_UDP`             | 2           | `DDoS-UDP_Flood1.pcap.csv`, `DDoS-UDP_Flood20.pcap.csv` |
| `DictionaryBruteForce` | 1           | `DictionaryBruteForce.pcap.csv`                         |
| `DNS_Spoofing`         | 1           | `DNS_Spoofing.pcap.csv`                                 |
| `MITM_ArpSpoofing`     | 2           | `MITM-ArpSpoofing.pcap.csv`, `MITM-ArpSpoofing1.pcap.csv` |

- Total CSVs used: **16** (under **10** class directories).  
