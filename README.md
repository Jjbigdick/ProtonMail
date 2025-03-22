# ProtonMail CAPTCHA Solver

Parallel Automated solving ProtonMail CAPTCHA (native), HCAPTCHA (currently using 2captcha API) and register account.
success rate: 100% on all ProtonMail CAPTCHAs. 
using: j's detection, OpenCV, Selenium 

### DEMO
#### Three Browsers parallism solving ProtonMail CAPTCHA and Hcaptcha.
[![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/6a5c0b1a-f13e-4a04-8930-9422bea3611f)](https://streamable.com/cl47bj)

### Key Achievements  
- 99% Success Rate via custom pixel analysis.  
- Solves 8 CAPTCHAs (one machine) in parallel with Python multiprocessing.  
- Completed stealth via proxy rotation.
  
### Features  
- **J’s Detection Algorithm** (self-built ProtonMail solver)  
- **Multi-CAPTCHA Parallel Solving**  
- **Anti-Detection Engine** (IP rotation and mouse obfuscation)  
- **Computer Vision Pipeline** (OpenCV + brute-force detection)  

### Technical Stack  
- Python, Selenium, OpenCV, Proxy APIs, 2Captcha API  

### Why This Project?  
- Solves a real-world challenge in automating secure email account creation.  
- Demonstrates reverse-engineering, performance optimization, and anti-detection strategies.
- 
### Future Roadmap  
- **Machine Learning Integration**: Train a CNN for adaptive CAPTCHA solving (reduce brute-force reliance).  
- **Multi-Platform Support**: Extend solver to reCAPTCHA v3 and Cloudflare Turnstile.  
![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/677d965e-0b14-4e25-8c65-2761828a3ca0)

