# Operation Redbridge (2024) - Digital Forensics Case Study



A full digital forensics investigation conducted as part of an academic case study. This project simulates a sexual assault investigation scenario involving forensic imaging, metadata analysis, deleted file recovery, steganography detection, encrypted content inspection, and comprehensive reporting. The case demonstrates the process and methodology followed by professional digital forensic investigators.

> **Disclaimer:** This is a simulated case study created for academic and portfolio purposes. No real individuals or organizations are involved.

---

## Project Summary

- **Project Title:** Operation Redbridge (2024)
- **Objective:** Conduct forensic analysis on submitted evidence to identify, extract, and report digital artefacts relevant to a criminal investigation.
- **Case Theme:** Simulated sexual assault investigation with evidence hidden in encrypted, deleted, and steganographic files.

---

## Tools Used

| Category         | Tools & Software            |
| ---------------- | --------------------------- |
| Analysis         | Autopsy, HXD (Hex Editor)   |
| Recovery         | PhotoRec                    |
| Encryption Check | VeraCrypt                   |
| Steganography    | StegSolve, OpenStego, zsteg |
| Hashing          | MD5, SHA-1 tools            |
| Decryption       | Cyberchef                   |

---

## Key Steps in the Investigation

1. **Imaging & Verification:**

   - Created forensic image of USB evidence (.E01 format)
   - Verified integrity via hash values (MD5 & SHA-1)

2. **File System Exploration:**

   - Recovered and reviewed deleted files
   - Analyzed user documents, browser artefacts, and image metadata

3. **Metadata & Timestamp Analysis:**

   - Timeline construction based on MAC times
   - Suspicious image & file timestamp anomalies noted

4. **Steganographic Analysis:**

   - Extracted hidden messages from images using StegSolve
   - Identified potential embedded files using OpenStego

5. **Encrypted Content:**

   - Located a VeraCrypt volume
   - Brute-force analysis of encrypted documents

6. **Reporting:**

   - Created a structured digital forensic report with evidence logs, screenshots, and recommendations

---

## Folder Structure

```
operation-redbridge-forensics/
├── reports/                       # PDF report of the case
├── README.md                      # Project overview
├── LICENSE                        # MIT License
```

---

## Report Preview

It is a structured forensic report containing:

- Executive Summary
- Chain of Custody
- Evidence Hash Values
- Screenshots of Analysis
- Recovered Artefacts & Metadata
- Conclusion & Recommendations

> Report located in `/reports/Operation_Redbridge_Forensic_Report.pdf`

---

## Forensic Image Download

Due to GitHub's file size restrictions, the `.E01` forensic image file is hosted externally. You can download it here:

https://drive.google.com/file/d/15b5g3zpDLakJsyyWOWCqFILSOb2QekNZ/view?usp=drive_link

---

## Skills Demonstrated

- Live & Dead Forensic Analysis
- Image and File Recovery
- Metadata & Timeline Analysis
- Steganography & Encrypted File Investigation
- Hex code analysis
- Report Writing & Documentation

---

## Timeline

- **Investigation Duration:** 2 weeks
- **Report Finalized:** March 2024

---

## Usage & Educational Value

This repository is intended for:

- Students learning digital forensics
- Recruiters seeking real project samples
- Trainers demonstrating investigation process
- Personal portfolio presentation

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

**Arka Paul**\
Cybersecurity & Digital Forensics Enthusiast\
[GitHub Profile](https://github.com/Arka-Paul)
