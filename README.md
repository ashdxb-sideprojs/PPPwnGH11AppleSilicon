# PS4 FW 11.00 GoldHen Jailbreak Guide (macOS with Apple Silicon)

This guide provides step-by-step instructions for jailbreaking a PS4 with firmware 11.00 using the GoldHen v2.4b17.3.7 PPPwn exploit. Please note that this guide is intended for use with macOS running on an Apple Silicon processor.

## Steps:

1. Open Terminal on your macOS device.
2. Clone the repository containing the jailbreak files by running the following command:
   ```bash
   git clone https://github.com/ashdxb-sideprojs/PPPwnGH11AppleSilicon.git
   ```
3. Change directory to the cloned folder:
   ```bash
   cd PPPwnGH11AppleSilicon
   ```
4. Copy the contents of the subfolder to the root of an exFAT USB stick.
5. Plug the USB stick into the PS4 console.
6. Connect the PS4 to your computer using a LAN cable.
7. On the PS4, go to "Settings" -> "Network" -> "Set Up Internet Connection" -> "Use a LAN Cable" -> "Custom" -> "PPPoE".
8. Enter any user ID and password (it doesn't matter) and select "Automatic" for DNS Settings and MTU Settings.
9. Select "Do Not Use" for Proxy Server.
10. Go back to the Terminal and run the following command to make the exploit script executable:
    ```bash
    chmod +x ./run_exploit.sh
    ```
11. Run the exploit script:
    ```bash
    ./run_exploit.sh
    ```
12. When prompted, run the exploit at the same time as you click "Test Internet Connection" on the PS4 console.

Please note that jailbreaking your PS4 may void your warranty and can have legal implications. Proceed at your own risk.


Credits:
- [GoldHEN](https://github.com/GoldHEN/GoldHEN/)
- [Mehdi Nih](https://www.youtube.com/watch?v=eFL9SFuA1c8)
- [PPPwn_cpp](https://github.com/xfangfang/PPPwn_cpp?tab=readme-ov-file)
- [PPPwn](https://github.com/TheOfficialFloW/PPPwn)
