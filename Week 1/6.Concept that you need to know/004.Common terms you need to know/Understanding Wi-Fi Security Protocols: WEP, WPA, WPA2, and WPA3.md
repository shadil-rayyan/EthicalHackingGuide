# Understanding Wi-Fi Security Protocols: WEP, WPA, WPA2, and WPA3

In the realm of Wi-Fi security, various protocols have evolved over the years to safeguard networks from unauthorized access and potential cyber threats. The key players in this evolutionary process include Wired Equivalent Privacy (WEP), Wi-Fi Protected Access (WPA), and its successor WPA2. Recently, WPA3 has entered the scene, introducing even more robust security measures. In this comprehensive guide, we'll unravel the intricacies of these protocols, catering to both beginners and experts.

## Why It Matters:

Securing your Wi-Fi network is paramount, as vulnerabilities in outdated protocols can expose your network to unauthorized access and potential data breaches. Understanding the differences between WEP, WPA, WPA2, and WPA3 is crucial for selecting the most robust security protocol compatible with your router.

## Wi-Fi Security Through the Ages:

### Wired Equivalent Privacy (WEP):
- **Introduction (1999):** WEP, born in 1999, was the first widely adopted Wi-Fi security protocol.
- **Flaws and Vulnerabilities:** Despite its prevalence, WEP suffered from security flaws, with exploits emerging as early as 2001.
- **Weaknesses:** U.S. export restrictions initially limited WEP to 64-bit encryption, later increased to 128-bit. Even with advancements, WEP remained highly vulnerable.
- **Retirement:** The Wi-Fi Alliance officially retired WEP in 2004.

### Wi-Fi Protected Access (WPA):
- **Introduction (2003):** WPA emerged in response to WEP's vulnerabilities and was adopted in 2003.
- **Improvements:** WPA introduced 256-bit keys, message integrity checks, and the Temporal Key Integrity Protocol (TKIP).
- **TKIP Vulnerabilities:** Despite improvements, TKIP vulnerabilities lingered due to its integration with existing WEP-enabled devices.
- **WPA's Legacy:** WPA, though an improvement, faced intrusion vulnerabilities, especially through Wi-Fi Protected Setup (WPS).

### Wi-Fi Protected Access II (WPA2):
- **Introduction (2006):** WPA2 superseded WPA in 2006, mandating AES algorithms and introducing CCMP as a TKIP replacement.
- **Security Implications:** WPA2 demonstrated robust security, with vulnerabilities primarily affecting enterprise-level networks.
- **WPS Vulnerability:** WPA2 retained the WPS vulnerability, demanding its disablement for enhanced security.

### Wi-Fi Protected Access III (WPA3):
- **Introduction (2018):** WPA3, the latest addition, aims to address security gaps present in WPA2.
- **Enhancements:** WPA3 brings stronger encryption, individualized data encryption, and protection against brute-force attacks.

## Wi-Fi Security Today:

As of today, the hierarchy of Wi-Fi security methods on modern routers, ranked from best to least secure, includes:

1. WPA2 + AES
2. WPA + AES
3. WPA + TKIP/AES (with TKIP as a fallback)
4. WPA + TKIP
5. WEP
6. Open Network (no security)

**Recommendation:** Disable Wi-Fi Protected Setup (WPS) and set your router to WPA2 + AES for optimal security.

## Real-World Task:

**Task:** Secure your Wi-Fi network using the recommended WPA2 + AES protocol.

**Answer:**
1. Access your router settings via a web browser using the default gateway IP address.
2. Navigate to the wireless security settings.
3. Choose WPA2 as the security protocol.
4. Select AES as the encryption method.
5. Disable Wi-Fi Protected Setup (WPS) to eliminate potential vulnerabilities.

Now, your Wi-Fi network is secured with a robust protocol, safeguarding it against unauthorized access.

## Questions:

1. **Why is it crucial to upgrade from WEP to more advanced security protocols like WPA2?**
2. **What vulnerabilities did WPA inherit from WEP, and how were they addressed in WPA2?**
3. **Explain the significance of disabling Wi-Fi Protected Setup (WPS) for enhanced security.**
4. **What improvements does WPA3 bring to Wi-Fi security, and why is it considered more secure than WPA2?**
