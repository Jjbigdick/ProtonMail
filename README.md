# ProtonMail CAPTCHA Solver

Parallel Automated solving ProtonMail CAPTCHA (native), HCAPTCHA (currently using 2captcha API) and register account.
success rate: 100% on all ProtonMail CAPTCHAs. 
using: j's detection, OpenCV, Selenium 

![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/677d965e-0b14-4e25-8c65-2761828a3ca0)

### DEMO
#### Three Browsers parallism solving ProtonMail CAPTCHA and Hcaptcha.
[![Screenshot 2023-07-20 213147](https://github.com/user-attachments/assets/6a5c0b1a-f13e-4a04-8930-9422bea3611f)](https://streamable.com/cl47bj)

### Key Achievements  
- 100% Success Rate via custom pixel analysis.  
- Solves 8 CAPTCHAs (one machine) in parallel with Python multiprocessing.  
- Completed stealth via proxy rotation.
  
### Features  
- **J’s Detection Algorithm** (self-built ProtonMail solver)  
- **Multi-CAPTCHA Parallel Solving**  
- **Anti-Detection Engine** (IP rotation and mouse obfuscation)  
- **Computer Vision Pipeline** (OpenCV + brute-force detection)  

- **Machine Learning Integration**: Train a CNN for adaptive CAPTCHA solving (reduce brute-force reliance).  
- **Multi-Platform Support**: Extend solver to reCAPTCHA v3 and Cloudflare Turnstile.  


