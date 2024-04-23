# cyber-security
BCCC-CIRA-CIC-DoHBrw-2020 -- DOH

https://www.kaggle.com/datasets/supplejade/bccc-cira-cic-dohbrw-2020-dns-over-http

- Checkpoint: 29 April-3 May https://docs.google.com/presentation/d/12BhexyWPI6CW8Veqa7ExNpYOxxYT2yOUz2FK7WsCssY/edit?usp=sharing

- Delivery: 21 May

- Final presentations and demonstrations: 27-28 May

Classify examples in terms of the concept under analysis. 

Exploratory data analysis: class distribution, values per attribute, etc.

Different learning algorithms should be employed and compared using appropriate evaluation metrics (performance during learning, confusion matrix, precision, recall, accuracy, F1 measure) and the time spent to train/test the models.

Supervised learning includes the following steps: 
- dataset analysis to check for the need for data pre-processing,
- identification of the target concept,
- definition of the training and test sets,
- selection and parameterization of the learning algorithms to employ
- evaluation of the learning process (in particular on the test set).

At least 3 supervised learning (classification) algorithms should be employed (Decision Trees, Neural Networks, K-NN, SVM, …), but more may be employed and compared using the Scikit-Learn Python library and considering the characteristics of the dataset. 

Results should be compared using tables or plots (e.g., using Seaborn or Matplotlib libraries).

--------------------

Domain over HTTPS (DoH) is a security protocol for the internet that encrypts DNS (Domain Name System) traffic using the HTTPS protocol. 

This means that DNS requests, which are traditionally sent in plaintext, are encrypted, enhancing the privacy and security of users on the internet.

- Two-Layered Approach: The first layer classifies traffic as DoH or non-DoH using statistical features, while the second layer characterizes the DoH traffic as benign or malicious using time-series classification.
- Tools and Browsers Used: The project employs several tools and browsers to generate DoH traffic, including Google Chrome, Mozilla Firefox, dns2tcp, DNSCat2, and Iodine.
- DoH Servers: The servers involved in responding to DoH requests include AdGuard, Cloudflare, Google DNS, and Quad9.
- Data Capture and Analysis: The project uses tools like DoHLyzer and DoH Data Collector to generate and analyze DoH traffic under various scenarios. Traffic is captured using tcpdump, and the analysis is aided by a Python script for processing pcap files.
- Objective: The main goal is to provide a comprehensive dataset that allows for the analysis, testing, and evaluation of DoH traffic to identify and address vulnerabilities in the DNS system, focusing on privacy and data manipulation issues.

License
- DoHMeter
- Research paper outlining the details of captured DoH traffic:
Mohammadreza MontazeriShatoori, Logan Davidson, Gurdip Kaur, and Arash Habibi Lashkari, “Detection of DoH Tunnels using Time-series Classification of Encrypted Traffic”, The 5th IEEE Cyber Science and Technology Congress, Calgary, Canada, August 2020
