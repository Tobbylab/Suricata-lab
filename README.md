Analyse a Pcap file and match it againt Suricata Signature . in this demo i will be be using surucate against 2017-06-38 traffic analysis-exercise pcap and in doing head to 

cd $Home/Desktop/CDD/Suricata/pcap
<img width="1440" alt="Screenshot 2025-01-06 at 12 15 36" src="https://github.com/user-attachments/assets/762a30f7-9e86-41fa-b165-eb18bfc82d3b" />

Then execute the command Sudo suricata -r 2017-06-28-traffic-exercise.pcap
Successful execution will result in the creation of four new files in the current directory
<img width="1920" alt="Screenshot 2025-01-06 at 12 05 33 (2)" src="https://github.com/user-attachments/assets/9bae5f2f-7c09-4b8b-8cb1-1d4eb5432a4c" />

Checking the first ten lines from the fast.log by executing the following Cat fast.log | head -n10
you will notice the stages of downloading the malware and the C&C communication
<img width="1440" alt="Screenshot 2025-01-06 at 12 33 23" src="https://github.com/user-attachments/assets/b09cb67f-23cc-4471-9a82-c2e255bf6171" />
