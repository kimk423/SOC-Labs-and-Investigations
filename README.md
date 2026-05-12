# SOC-Labs-and-Investigations
# The Greenholt Phish

## Objective
Analyze a phishing email and identify indicators of compromise.

---

## Email Details

### Sender Display Name
Mr James Jackson
<img width="895" height="253" alt="image" src="https://github.com/user-attachments/assets/378f942f-28eb-4cee-bece-c6fec7671cc4" />


### Sender Email
info@mutawamarine.com
<img width="895" height="253" alt="image" src="https://github.com/user-attachments/assets/57af4577-5a61-4e6c-aea7-9e66c43a51fe" />


### Reply-To Email
info.mutawamarine@mail.com
<img width="861" height="202" alt="image" src="https://github.com/user-attachments/assets/d277cad7-c130-4d7d-8bb7-b1c1892adc49" />


### Originating IP
192.119.71.157

---<img width="975" height="218" alt="image" src="https://github.com/user-attachments/assets/133c25a5-8a79-442e-9bbb-b5d675abd964" />


## Infrastructure Analysis

### IP Owner
Hostwinds LLC

### SPF Record
v=spf1 include:spf.protection.outlook.com -all

<img width="975" height="183" alt="image" src="https://github.com/user-attachments/assets/70633a89-f379-4225-8c9b-d8a71f6868a5" />

### DMARC Record
v=DMARC1; p=quarantine; fo=1

---<img width="975" height="340" alt="image" src="https://github.com/user-attachments/assets/b98d0428-940d-47a1-bd86-f8bcba1c889b" />


## Attachment Analysis

### Attachment Name
SWT_#09674321____PDF__.CAB
<img width="975" height="579" alt="image" src="https://github.com/user-attachments/assets/75a5aa10-6d1e-45ee-8ef1-f7231de0e6d7" />


### SHA256 Hash
2e91c533615a9bb8929ac4bb76707b2444597ce063d84a4b33525e25074fff3f
ubuntu@tryhackme:~$ sha256sum SWT_#09674321____PDF__.CAB 
2e91c533615a9bb8929ac4bb76707b2444597ce063d84a4b33525e25074fff3f  SWT_#09674321____PDF__.CAB
Note: here first I have to downloaded the email attachment after that find the valu of hash.


### File Size
400.26 KB
<img width="975" height="355" alt="image" src="https://github.com/user-attachments/assets/d12db2b0-1b2c-4619-a434-d8592449999c" />


### Actual File Type
RAR Archive

---<img width="975" height="389" alt="image" src="https://github.com/user-attachments/assets/e1adfc97-c7bc-4210-b632-81fe74a0716d" />


## Tools Used
- VirusTotal
- SPF Lookup
- DMARC Lookup
- sha256sum

---
The email was identified as a phishing attempt using a suspicious attachment and spoofed sender information.
