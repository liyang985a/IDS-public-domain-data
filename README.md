# IDS-public-domain-data
Introduce the public domain datasets available in IDS


（1）KDD99
The KDD99 dataset was created by Lee and Stolfo (2000) from the DARPA network dataset files. This dataset contains seven weeks of network traffic, with approximately 4.9 million records. The attack types are classified into: (1) User to Root (U2R); (2) Remote to Local (R2L); (3) Probe; (4) DoS. Each instance is represented by 41 features in three categories: (1) Basic; (2) Traffic; (3) Content. The basic features are extracted from TCP/IP connections. Traffic features are further categorized into those with the same host or service characteristics. Content features relate to suspicious behaviors in the data payload. KDD99 is the most widely used dataset for evaluating intrusion detection models.

Dataset link: http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

（2）NSL-KDD
NSL-KDD addresses some inherent issues with the KDD99 dataset. Although this newer version of the KDD dataset still faces some challenges discussed by Tavallaee et al. (2009) and may not be a perfect representation of existing real-world networks, it can still serve as an effective benchmark dataset due to the scarcity of public datasets for network-based IDSs. This allows researchers to compare different intrusion detection methods. Additionally, NSL-KDD offers a reasonable number of records in its training and testing sets. This advantage makes it affordable to run experiments on the entire dataset without the need for random selection of a subset. Consequently, evaluation results from different research efforts will exhibit consistency and comparability.

Dataset link: https://www.unb.ca/cic/datasets/nsl.html

（3）UNSW-NB15
The UNSW-NB15 dataset was created by the Cyber Range Lab of the Australian Centre for Cyber Security. It is widely used due to its various novel attack patterns. The attack types include Fuzzer, Analysis, Backdoor, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms. It features a training set with 82,332 records and a testing set with 175,341 records.

Dataset link: https://cloudstor.aarnet.edu.au/plus/index.php/s/2DhnLGDdEECo4ys?path=2FUNSW-NB1520-20CSV20Files

（4）CICIDS2017
The CICIDS2017 dataset includes both benign and common attacks, containing source data (PCAP) and results of network traffic analysis (CSV files) based on timestamps, source and destination IPs, source and destination ports, protocols, and attack token flows. Researchers utilized the B-Profile system (Sharafaldin, et al. 2016) to analyze abstract behaviors of human interactions and generate benign background traffic. This dataset encompasses abstract behaviors of 25 users based on HTTP, HTTPS, FTP, SSH, and email protocols. Brute-force attacks include FTP, SSH, DoS, Heartbleed, web attacks, infiltration, botnets, and DDoS.

The CICIDS2017 dataset includes both benign and common attack scenarios, consisting of source data (PCAP) and the results of network traffic analysis (CSV files) based on timestamps, source and destination IPs, source and destination ports, protocols, and attack token flows. Researchers utilized the B-Profile system (Sharafaldin, et al. 2016) to analyze abstracted behaviors of human interactions and generate benign background traffic. This dataset encompasses abstracted behaviors of 25 users based on HTTP, HTTPS, FTP, SSH, and email protocols. The attack scenarios include brute-force FTP, SSH, DoS, Heartbleed, web attacks, infiltration, botnet, and DDoS. 

Dataset link: https://www.unb.ca/cic/datasets/ids-2017.html

（5）CICDDoS2019
The CICDoS2019 dataset incorporates the latest DDoS attacks, resembling real-world scenarios. It comprises the results of network traffic analysis conducted using CICFLOWMeter-V3, which includes token flows based on timestamped sources, along with destination IPS, source and port protocols, and attacks.

Dataset link: https://www.unb.ca/cic/datasets/ddos-2019.html

（6）Kyoto 2006+
The Kyoto 2006+ dataset is a publicly available honeypot dataset containing real network traffic, which encompasses only a small volume and scope of genuine, normal user behaviors. Researchers have transformed packet-based traffic into a new format known as sessions. Each session possesses 24 attributes, among which 14 are statistical features inspired by the KDD CUP 99 dataset, while the remaining 10 attributes are typical traffic-based properties, such as IP addresses (anonymized), ports, and durations. This dataset, collected over a span of three years, comprises approximately 93 million sessions.

Dataset link: http://www.takakura.com/Kyoto_data/

（7）NDSec-1
The NDSec-1 dataset comprises trace and log files of network attacks synthesized by researchers from network infrastructure. It is publicly available and was captured in a packet-based format in 2016. The dataset includes additional system logs and Windows event log information. The attack combinations encompass botnets, brute-force attacks (targeting FTP, HTTP, and SSH), DoS (HTTP, SYN, and UDP floods), exploits, port scans, spoofing, and XSS/SQL injection.

Dataset link: https://www2.hs-fulda.de/NDSec/NDSec-1/Files/

（8）CTU-13
The CTU-13 dataset, captured in 2013, is available in packet, unidirectional flow, and bidirectional flow formats. Captured within a university network, its 13 scenarios encompass various botnet attacks. Additional information regarding infected hosts is provided on the website. The traffic is labeled in three stages: 1) All traffic to and from infected hosts is labeled as botnet; 2) Traffic matching specific filters is labeled as normal; 3) Remaining traffic is labeled as background. Hence, background traffic could be either normal or malicious.

Dataset link: http://mcfp.weebly.com/

（9）BoT-IoT
The BoT-IoT dataset comprises over 72 million records, including DDoS, DoS, OS, service scan, keylogging, and data exfiltration attacks. The Node-RED tool was utilized to simulate the network behavior of IoT devices. MQTT, a lightweight communication protocol, was employed for linking Machine-to-Machine (M2M) communications. The IoT scenarios within the test platform encompassed a weather station, smart refrigerator, motion-activated lights, remotely activated garage door, and smart thermostat.

Dataset link: https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/bot_iot.php

（10）IoT-23
The IoT-23 dataset consists of 23 network captures (referred to as scenarios) of IoT traffic, including 20 from infected IoT devices (PCAP files) and three representing real IoT network traffic. The Raspberry Pi malware executes using various protocols and performs different actions in each malicious scenario. The network traffic captured in benign scenarios originates from three real IoT devices: Philips Hue smart LED lights, Amazon Echo smart home assistants, and Somfy smart door locks. Both malicious and benign scenarios were run in a controlled network environment with unrestricted internet connectivity, mimicking any real-world IoT device setup.

Dataset link:https://mcfp.felk.cvut.cz/publicDatasets/IoT-23-Dataset/iot_23_datasets_small.tar.gz


