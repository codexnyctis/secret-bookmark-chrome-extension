# 🔐 Secret Bookmark Chrome Extension

> 🚧 Work in Progress  
> Created as part of the Scrimba JavaScript course. This version is currently under development and will be improved as new techniques are learned.

Secret Bookmark is a lightweight Chrome extension that lets you save web pages for later. You can add a link manually or save the current tab with one click. Your data is stored locally on your device for privacy and persistence.

## How to Use

1. Download this folder to your computer  
2. Open Chrome and go to `chrome://extensions/`  
3. Turn on Developer Mode (top right)  
4. Select Load unpacked  
5. Choose the secret_bookmark folder  
6. The extension will now appear in your browser toolbar

## Features

Save a URL manually using the input box  
Save the current browser tab with one click  
Click on any saved link to open it in a new tab  
Double click the Delete All button to clear all saved leads  
Data is stored using localStorage so it stays even after closing the browser

## Folder Structure

Your folder should contain the following files

secret_bookmark  
• icon.png  
• index.html  
• index.css  
• index.js  
• manifest.json  
• package.json  

## Developer Setup

If you want to make changes or build it yourself

Install dependencies  
```
npm install
```

Start development server  
```
npm run dev
```

This runs the extension like a normal website. To test it as an extension, follow the How to Use steps above.

## Building for Chrome

To create a production version

```
npm run build
```

This will create a dist folder that can be uploaded to Chrome or zipped for publishing.

## Technologies Used

HTML, CSS, JavaScript  
Vite for development and build process  
Chrome Extension API (Manifest version 3)  
localStorage for storing data  
Tabs permission to save the current tab

## Planned Improvements

Allow deleting individual links  
Add option to export and import leads  
Add optional password protection  
Cloud backup using a service like Firebase  
Dark mode and smoother interface

## Credits

This project is being built as part of the Scrimba JavaScript course  
Visit scrimba.com to learn more about their frontend and fullstack developer paths

## Licence

This project is open source and free to use
