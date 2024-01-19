# Network-Intrusions-Detection-Case-Study

**Business Objective:**
With the enormous growth of computer networks usage and the huge increase in the number of applications running on top of it, network security is becoming increasingly more important. All the computer systems suffer from security vulnerabilities which are both technically difficult and economically costly to be solved by the manufacturers. Therefore, the role of Intrusion Detection Systems (IDSs), as special-purpose devices to detect anomalies and attacks in the network, is becoming more important.
The research in the intrusion detection field has been mostly focused on anomaly-based and misuse- based detection techniques for a long time. While misuse-based detection is generally favoured in commercial products due to its predictability and high accuracy, in academic research anomaly detection is typically conceived as a more powerful method due to its theoretical potential for addressing novel attacks.
As part of this project, your task is to build network intrusion detection system to detect anomalies and attacks in the network.
There are two problems:
Binomial classification: Detect anomalies by predicting Activity is normal or attack
Multinomial Classification: Detecting type of activity by predicting Activity is Normal or Back or Buffer Over flow or FTP Write or Guess Password or Neptune or N-Map or Port Sweep or Root Kit or Satan or Smurf

**Data Preparation:**
Appended all the files and create new column called attack based on the name of attack. While we are appending the files, we can take resampling of data based on the number of attacks.
For Binomial classification, we can create attack variable with attack vs. normal
For Multinomial classification, we can create attack variable with normal vs. Back vs. Buffer Over flow vs. FTP Write vs. Guess Password vs. Neptune vs. N-Map vs. Port Sweep vs.   Root Kit vs. Satan vs. Smurf
