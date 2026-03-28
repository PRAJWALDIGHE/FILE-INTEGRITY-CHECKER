# FILE-INTEGRITY-CHECKER

*COMPANY*: Codtech IT Solutions Private Limited

*NAME*: Prajwal Changdev Dighe

*INTERN ID*: CTIS5894

*DOMAIN*: Cyber Security & Ethical Hacking

*DURATION*: 4 Weeks

*MENTOR*: Neela Santhosh Kumar  

*DESCRIPTION*:
The File Integrity Checker is a cybersecurity tool developed using Python to monitor and detect changes in files by calculating and comparing cryptographic hash values. The primary objective of this task is to ensure data integrity, which is a fundamental aspect of information security. Data integrity refers to the accuracy and consistency of data over its lifecycle, and any unauthorized modification can lead to serious security risks.

In this task, the tool was implemented using Python’s built-in hashlib library, which provides various hashing algorithms such as SHA-256. Among these, SHA-256 was used due to its strong security properties and widespread adoption in modern systems. The tool works by generating a unique hash value for a file based on its contents. Even a minor change in the file, such as adding or removing a single character, results in a completely different hash value.

The process begins by taking a file path as input from the user. The program then reads the file in binary mode and processes it in chunks to efficiently handle files of any size. The SHA-256 hash of the file is calculated and displayed as the original hash value. After this, the user is given an option to modify the file. Once the modification is done and the user confirms, the program recalculates the hash of the file and compares it with the original hash. If both hash values are identical, it indicates that the file has not been modified. Otherwise, the tool alerts the user that the file has been changed.

This tool has several real-world applications in cybersecurity. It is widely used in systems that require verification of file authenticity, such as software distribution platforms, where users can verify downloaded files against known hash values to ensure they have not been tampered with. It is also used in intrusion detection systems to monitor critical system files and detect unauthorized changes. In digital forensics, file integrity checking is essential for maintaining evidence authenticity during investigations.

The implementation also includes error handling to manage common issues such as invalid file paths or missing files. This ensures that the program runs smoothly without crashing, making it user-friendly and reliable. Additionally, the use of chunk-based file reading improves performance and allows the tool to handle large files efficiently.

One of the key advantages of this tool is its simplicity and effectiveness. It demonstrates how a basic concept like hashing can be used to build a powerful security mechanism. While this implementation is a basic version, it can be further enhanced by automating periodic checks, maintaining logs of file changes, or integrating it with a graphical user interface for better usability.

In conclusion, the File Integrity Checker successfully demonstrates the practical application of cryptographic hashing in ensuring data integrity. It highlights the importance of detecting unauthorized file modifications and provides a foundation for building more advanced security monitoring systems. This task not only strengthens programming skills in Python but also provides valuable insights into one of the core principles of cybersecurity.

*OUTPUT*:
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/72cafaf3-ddc5-456d-ab47-b303aa502c52" />
