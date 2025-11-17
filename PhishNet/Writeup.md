# PhishNet

Created by: Anh Tuan
Last edited: November 17, 2025 11:31 PM

> **An accounting team receives an urgent payment request from a known vendor. The email appears legitimate but contains a suspicious link and a .zip attachment hiding malware. Your task is to analyze the email headers, and uncover the attacker's scheme.**
> 

Truy cập https://eml-analyzer.herokuapp.com/ và tải file `.eml` lên để phân tích.

- **What is the originating IP address of the sender?**
    
    Sau khi trang web phân tích xong, kéo xuống xem kết quả ở phần `X headers`
    
    ![image.png](image.png)
    
- **Which mail server relayed this email before reaching the victim?**
- **What is the sender's email address?**
- **What is the 'Reply-To' email address specified in the email?**
- **What is the SPF (Sender Policy Framework) result for this email?**
- **What is the domain used in the phishing URL inside the email?**
- **What is the fake company name used in the email?**
- **What is the name of the attachment included in the email?**
- **What is the SHA-256 hash of the attachment?**
- **What is the filename of the malicious file contained within the ZIP attachment?**
- **Which MITRE ATT&CK techniques are associated with this attack?**