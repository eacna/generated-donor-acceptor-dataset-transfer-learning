# generated-donor-acceptor-dataset-transfer-learning

## Description

Datasets of generated donor and acceptor molecules with predicted energies obtained via transfer learning models. Encrypted and compressed for secure access by authorized persons.

---

## Important Notice

This repository has been made public only to ensure long-term availability of the data 
referenced in the author's thesis. The encrypted data files included here are not 
intended for public use. Access is restricted to authorized reviewers with the appropriate passwords.

Unauthorized use, redistribution, or modification of the contents of this repository 
is strictly prohibited.

---

## Data Files and Encryption

Due to the sensitivity of the data and to optimize file size, the original CSV 
files, 
`predicted_acceptors.csv` and `predicted_donors.csv`, 
were first compressed using `gzip`. Subsequently, each compressed file 
(`predicted_acceptors.csv.gz` and `predicted_donors.csv.gz`) was encrypted 
individually using 7-Zip with AES-256 encryption and a strong password, resulting in the files:
- `predicted_acceptors.7z`
- `predicted_donors.7z`

---

## How to Access the Data

To access the data, please follow these steps:

1. Download the encrypted files `predicted_acceptors.7z` and `predicted_donors.7z` from this repository.
2. Use 7-Zip (available on Windows, Linux, and macOS) or a compatible archive manager to decrypt each archive by entering the password when prompted.
3. After extracting, decompress the files `predicted_acceptors.csv.gz` and `predicted_donors.csv.gz` using a tool that supports gzip (e.g., `gunzip` on Linux/macOS or 7-Zip on Windows).
4. The resulting files `predicted_acceptors.csv` and `predicted_donors.csv` will be accessible for analysis.

---
## Passwords

Only authorized individuals have access to the passwords required to open the encrypted files.

In the future, a version of the datasets without encryption may be made available once data sharing restrictions are lifted or reviewed.


---
