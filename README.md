# ProtonMail CAPTCHA Automation & Anti-Detection System (IP Obfuscation)
A high-performance CAPTCHA-solving system designed to automate ProtonMail account creation while bypassing detection mechanisms. Combines custom pixel-analysis algorithms with anti-detection layers to solve CAPTCHAs in parallel.


**DEMO**:
"Solving 3 CAPTCHAs in parallel (ProtonMail + hCaptcha)."
[![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/6a5c0b1a-f13e-4a04-8930-9422bea3611f)](https://streamable.com/cl47bj)

### Features
- **Parallel CAPTCHA Solving**: Utilizes multiprocessing to solve multiple CAPTCHAs simultaneously (ProtonMail, hCaptcha).  
- **J’s Detection Algorithm**: Custom pixel-analysis engine for real-time CAPTCHA grid detection.  
- **Anti-Detection Layer**:  
  - IP Rotation via proxy APIs to evade ProtonMail’s IP tracking.  
  - Simulated human mouse movements using Selenium WebDriver.  
- **Computer Vision Integration**: OpenCV for object coordinate mapping and trajectory calculation.  

![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/677d965e-0b14-4e25-8c65-2761828a3ca0)

