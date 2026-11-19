# Password-Hashes-Cracking---Cybersecurity-Training-Lab
Password Hashes and Cracking Training with John The Ripper (JTR), Networkwalks (NW) tools - Live Session with Waqas Karim CCIE, NETWORKWALKS
🔐 Password Hashes & Cracking — Cybersecurity Training Log

Status Topic Tools Purpose
A huge milestone and great achievement in today's cybersecurity training session: learning how password hashes work and how tools like John the Ripper (JTR) are used to test password strength.

📑 Table of Contents
Module 1: Password Hashes & JTR
Module 2: Password Hashes with Networkwalks (NW) Tools
Lesson Learned
Disclaimer
Module 1: Password Hashes & JTR
John the Ripper (JTR) is a popular password-cracking tool used by security professionals to test password strength. It supports many hash types and can also unlock password-protected files such as PDF, ZIP, and Office documents.
[!NOTE] Johnny is the graphical version of JTR. It provides a simple point-and-click interface, so beginners can use JTR's power without typing long terminal commands.

🛠️ Steps

1
Download John the Ripper from the official website on your Windows PC — choose the file matching your OS (Windows, Linux, or macOS).
2
Download Johnny (GUI) from the official website. Run the setup file to install it. Open Johnny, go to Settings, click Browse, and select john.exe.
3
Download the encrypted PDF file to your PC. Open a hash-extraction website and upload the PDF to find its hash. Select and copy the hash value.
4
Paste the hash into a .txt file and save it. Open Johnny, click Open Password File, browse to your hash.txt, and click Open. Click Start New Attack.
[!WARNING] If the hash contains extra characters at the start (for example, a leading b), remove them before saving to the .txt file — they're often just byte-string markers and aren't part of the actual hash.

✅ Result
Once JTR finishes, it reveals the PDF's password. Copy this password to unlock the encrypted PDF. Opening the file successfully confirms the crack worked. 🎉
Module 2: Password Hashes with Networkwalks (NW) Tools
Two free, browser-based tools from Networkwalks make this same process possible with no installation required:
1. Hash Calculator – extracts the hash from a locked PDF file.
2. Password Cracker – cracks the real password from that hash.

🛠️ Steps

1. Download the encrypted PDF file to your laptop
2. Open the Networkwalks Hash Calculator in your browser
3. Upload the locked PDF to the Hash Calculator
   → It returns a hash value starting with "$pdf$..."
4. Copy the complete hash value
5. Open the Networkwalks Password Cracker
   → Paste the hash value and start the attack
6. Wait for the tool to finish — the cracked password is displayed
7. Open the locked PDF and enter the cracked password to unlock it
Since both tools run entirely in the browser, there's nothing to install — just upload, crack, and unlock.

💡 Lesson Learned
This practice lab helped me understand, step by step, how password cracking actually works — and reinforced why strong, complex passwords matter for real-world protection against these exact techniques.

⚠️ Disclaimer
This write-up is shared strictly for educational and research purposes only. The tools and techniques described should only ever be used on files and systems you own or have explicit authorization to test.
