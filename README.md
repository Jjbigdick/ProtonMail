# ProtonMail CAPTCHA Automation & Anti-Detection System (IP Obfuscation)
A high-performance CAPTCHA-solving system with 99% success rate designed to automate ProtonMail account creation while bypassing detection mechanisms. Combines custom pixel-analysis algorithms with anti-detection layers to solve CAPTCHAs in parallel.


**DEMO**:

"Solving 3 CAPTCHAs in parallel (ProtonMail + hCaptcha)."
[![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/6a5c0b1a-f13e-4a04-8930-9422bea3611f)](https://streamable.com/cl47bj)

### Features
- **J’s Detection Algorithm**: Custom pixel-analysis engine for real-time CAPTCHA grid detection.  
- **Parallel CAPTCHA Solving**: Utilizes multiprocessing to solve multiple CAPTCHAs simultaneously (ProtonMail, hCaptcha).  
- **Anti-Detection Layer**:  
  - IP Rotation via proxy APIs to evade ProtonMail’s IP tracking.  
  - Simulated human mouse movements using Selenium WebDriver.  
- **Computer Vision Integration**: OpenCV for object coordinate mapping and trajectory calculation.

### Technical Details  
- **Tools**: Python, OpenCV, Selenium, Proxy and 2CAPTCHA APIs.  
- **Algorithms**: Brute-force coordinate mapping, multithreaded task distribution.

### Why This Project?  
- Solves a real-world challenge in automating secure email account creation.  
- Demonstrates reverse-engineering, performance optimization, and anti-detection strategies.  

### Future Improvements  
- Integrated with ML technics able to general solving multiple CAPTCHA types without further design.
- Expand to other CAPTCHA types (reCAPTCHA v3).  

![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/677d965e-0b14-4e25-8c65-2761828a3ca0)

