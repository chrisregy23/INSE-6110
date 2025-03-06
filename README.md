# Privacy & Security Analysis of Android Applications

This project focuses on analyzing the privacy and security aspects of various Android applications. Using tools like **MobSF**, **LiteRadar**, and **Firebase Scanner**, the team conducted static and dynamic analysis to identify vulnerabilities, trackers, and dangerous permissions. The goal is to highlight potential security risks and privacy concerns in popular Android apps.

## Key Features

- **Tools Used**:  
  - **Genymotion**: Android emulator for virtual Android environment interaction.  
  - **VirtualBox**: Allows running Android OS on different operating systems.  
  - **MobSF**: Automated mobile pen-testing framework for static analysis.  
  - **LiteRadar**: Analyzes third-party libraries for potential security issues.  
  - **Firebase Scanner**: Detects Firebase misconfigurations that could lead to data breaches.  
  - **APK Extractor**: Extracts APK files from installed Android applications.  
  - **APKtool**: Reverse engineers third-party, closed, binary Android apps.  

- **Analysis Methodology**:  
  - **Static Analysis**: High-level analysis of security issues, permissions, and trackers.  
  - **APK Decompilation**: Low-level analysis of manifest code and dynamic behavior.  
  - **APK Installation**: Instrumentation and data acquisition for deeper insights.  

- **Dangerous Permissions**:  
  - Identified risky permissions like `ACCESS_FINE_LOCATION`, `READ_EXTERNAL_STORAGE`, and `WRITE_EXTERNAL_STORAGE`.  
  - Highlighted potential misuse of permissions for tracking, phishing, and data modification.  

- **Trackers**:  
  - Analyzed Facebook and Google Firebase Analytics trackers for privacy violations.  
  - Discussed risks like profiling, targeted advertising, and data breaches.  

- **Third-Party Libraries**:  
  - Identified vulnerable libraries like `Joda Time`, `ZKing`, `Glide`, and `Bouncy Castle`.  
  - Highlighted risks such as buffer overflow, man-in-the-middle attacks, and remote code execution.  

- **Firebase Scan Results**:  
  - Scanned for misconfigurations in Firebase setups.  
  - Identified secure and potentially vulnerable Firebase instances.  

- **Security Analysis of Specific Apps**:  
  - **Augmenty**: Found location tracking without explicit permission and TLS pinning vulnerabilities.  
  - **Ipsy**: Identified WiFi service permission violations and insecure JSON object transmission.  
  - **Good Style**: Detected SHA-1 vulnerabilities and TLS bypass issues.  

## Deliverables

1. **Comprehensive Analysis Reports**: Detailed reports on dangerous permissions, trackers, and third-party libraries.  
2. **Firebase Misconfiguration Scan Results**: Insights into secure and vulnerable Firebase setups.  
3. **Security Analysis of Specific Apps**: In-depth analysis of apps like Augmenty, Ipsy, and Good Style.  

## Learning Objectives

- **Understand Android App Vulnerabilities**: Learn about common security risks in Android applications.  
- **Analyze Permissions and Trackers**: Explore how permissions and trackers can impact user privacy.  
- **Evaluate Third-Party Libraries**: Assess the security risks associated with third-party libraries.  
- **Conduct Static and Dynamic Analysis**: Gain hands-on experience with tools like MobSF and Firebase Scanner.  
