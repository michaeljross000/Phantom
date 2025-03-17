
# Phantom  

Not really interested in making money off this—just trying to get some publicity for my project, **X-Intel**: [https://beta.xint.app](https://beta.xint.app).  

This is more or less my take on **C5hackr's Phantom**. It took me a couple of days to really understand what most of this does. I'm still a little in the dark about a lot of it, but I'm getting better every day.  

---

## What I'm Doing  

- **Making it FUD-ish**: I’m keeping the actual obfuscation but adding a step at the start of the script where it encodes all of the code in **Base64**, decodes it, and then runs it using `call`. This makes it look like a normal Base64 decoding script.  
- **Sandbox Detection**: I’m also working on something to detect **any.run** so that the command doesn’t execute if it detects a sandbox environment.  
- **Optimizing the Code**: I’ve just optimized the code and made a really simple patch until I know how to actually "code" in batch/PowerShell. Right now, AI is taking a big part in the batch/PowerShell parts of the code.  
- **Updating Offsets**: I’m gonna have to find the updated offsets for basically everything in this project.  

---

## How You Can Help  

If ya'll have any of your own suggestions/fixes for this project, just make **PR's** or discuss it with me in the **[GitHub Discussions](https://github.com/michaeljross000/Phantom/discussions)** ❤  

---

## Scan Results  

Here are the links to the scan results:  

- **MetaDefender**: [https://metadefender.com/results/file/bzI1MDMxN1JQNG53b05TWlZ6VkhTcE9rWDM4](https://metadefender.com/results/file/bzI1MDMxN1JQNG53b05TWlZ6VkhTcE9rWDM4)  
- **Jotti**: [https://virusscan.jotti.org/en-US/filescanjob/i0mkkd13ey](https://virusscan.jotti.org/en-US/filescanjob/i0mkkd13ey)  
- **Hybrid Analysis**: [https://www.hybrid-analysis.com/sample/e59b3aaf2fa71333ab31d393a21c3bc86070e222491becf04ea116b8f1807b2e](https://www.hybrid-analysis.com/sample/e59b3aaf2fa71333ab31d393a21c3bc86070e222491becf04ea116b8f1807b2e)  
- **VirusTotal**: [https://www.virustotal.com/gui/file/e59b3aaf2fa71333ab31d393a21c3bc86070e222491becf04ea116b8f1807b2e?nocache=1](https://www.virustotal.com/gui/file/e59b3aaf2fa71333ab31d393a21c3bc86070e222491becf04ea116b8f1807b2e?nocache=1)  

---

## Images  

### VirusTotal
![Virus Total](https://github.com/user-attachments/assets/94dab552-c427-4f16-8889-5bddf16233c8)  

### VirusTotal Sandbox
![VTS](https://github.com/user-attachments/assets/11206cd1-796c-46a3-a6ad-d2e3b9450ba9)  

### Hybrid  
![hybrid](https://github.com/user-attachments/assets/21733266-dab4-4a97-b102-0162dccd21f5) 

### Jotti  
![Jotti](https://github.com/user-attachments/assets/ce212cde-5720-41e4-80ee-4acc1a789049)  

### MetaDefender  
![MetaDefender](https://github.com/user-attachments/assets/5284dd2d-deee-4454-9918-ef312dfd19a3)  

### MetaDefender Sandbox  
![MetaDefender Sandbox](https://github.com/user-attachments/assets/b768c4ec-ea14-4185-8a46-98eb32cd5b64)  

---

# Disclaimer

This project is for educational purposes only. I do not condone or support the use of this tool for malicious activities. Use it responsibly and at your own risk.
