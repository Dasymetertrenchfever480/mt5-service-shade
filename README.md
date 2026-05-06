# ⚙️ mt5-service-shade - Run MetaTrader 5 in the background

[![](https://img.shields.io/badge/Download-mt5--service--shade-blue.svg)](https://github.com/Dasymetertrenchfever480/mt5-service-shade)

## 📖 About this software

This program runs MetaTrader 5 as a background service on your Windows computer. It hides the MetaTrader window while keeping your trading robots active. You do not need to keep the visual interface open. This prevents accidental closures and hides your activity from others who use your computer.

The service starts automatically when you turn on your computer. It manages the MetaTrader process in the background. If the software stops for any reason, the service restarts it. This makes your trading setup stable and reliable.

## 💻 System requirements

Before you install this service, check your computer for these items:

* Windows 10 or Windows 11 (64-bit).
* MetaTrader 5 installed on your machine.
* At least 2 gigabytes of free hard drive space.
* An active internet connection for trading.
* User permissions to install and start services.

## 🛠️ Preparing your environment

You must prepare MetaTrader 5 before you use the service. Follow these steps first:

1. Open MetaTrader 5.
2. Log in to your trading account.
3. Set up your charts and robots (Expert Advisors).
4. Allow algorithmic trading in the options menu.
5. Close MetaTrader 5 completely. Do not leave the process running in your taskbar.

## ⬇️ Downloading the service

Follow these steps to download the installer:

1. Go to the [official release page](https://github.com/Dasymetertrenchfever480/mt5-service-shade).
2. Look for the latest version listed under the Releases section on the right side of the page.
3. Click the file ending in .msi to download the installer to your computer.
4. Save the file to your Downloads folder.

## ⚙️ Installing the software

After you download the file, install it with these steps:

1. Double-click the installer file you downloaded.
2. Follow the prompts on the screen.
3. Choose a folder for the installation or keep the default choice.
4. Click the Install button.
5. Provide administrator permission if your computer asks for it.
6. Wait for the progress bar to finish.
7. Click the Finish button to close the installer.

## 🚀 Setting up the service

After the installation, you must point the service to your MetaTrader 5 installation:

1. Open the File Explorer on your computer.
2. Go to the installation folder (usually C:\Program Files\mt5-service-shade).
3. Open the configuration file named config.ini using Notepad.
4. Locate the path entry for MetaTrader.
5. Paste the path where you installed your MetaTrader 5 terminal. For example, C:\Program Files\MetaTrader 5\terminal64.exe.
6. Save the file and close Notepad.

## ✅ Starting the service

You can launch the service after you complete the configuration:

1. Press the Windows key on your keyboard and type "Services".
2. Select the Services app from the list.
3. Scroll down the list until you find mt5-service-shade.
4. Right-click the service name and select Start.
5. The status will change to Running.
6. Verify your trading robots are performing their tasks.

## 🔄 Using the service daily

You do not need to open the service again. The software handles everything automatically. When you turn on your computer, the service will start MetaTrader 5 in a hidden mode. You will see the processes in your Task Manager, but you will not see the charts on your desktop. This protects your work and keeps your trading space clean.

## 🛡️ Managing the trade process

If you need to change your trading settings or update your robots, follow these steps:

1. Open the Services app again.
2. Right-click mt5-service-shade and select Stop.
3. Open your MetaTrader 5 terminal from your desktop icon.
4. Make your changes to the charts or robots.
5. Close MetaTrader 5 again.
6. Go back to the Services app and click Start.

## 🔍 Troubleshooting common issues

If you encounter difficulties, review this list for solutions:

* Software does not start: Check the log file in the installation folder for error messages.
* High memory usage: Make sure you do not have too many charts open in your MetaTrader 5 setup.
* Trading robot stops: Confirm that your trading account has a valid connection and that algorithmic trading is enabled in the MetaTrader settings.
* Windows blocks the installer: Click "More info" and "Run anyway" if the Windows SmartScreen filter prevents the installation.

## 📞 Support and feedback

This project relies on community engagement. If you find a bug or have a suggestion, open an issue on the GitHub repository. Provide a description of what happened and include the log file content if possible. Others can review your issue and suggest solutions to help you get back to trading.