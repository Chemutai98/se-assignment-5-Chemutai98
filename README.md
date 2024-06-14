[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244875&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   1. Download visual studio code
   - Visit the official  https://code.visualstudio.com/
   -Click on download and download on whatever operating system you are using
   2. Run the installer
   - once the download is complete, open the downloaded file
   -Follow the installation wizard. Click next to proceed with the installation
   3. Accept License Agreement
   -Read the license agreement then check the "I accept the agreement" box and click next
   4. Select destination location 
   -Chose the destination folder where you want your VS to be intalled and click next
   5. Select additional tasks
   - choose additioonal tasks such as creating a desktop icon or adding VS code to a path and click next
   6. Install
   -Click "install" to start installation process. Once complete, click "finish" to launch VS code
   Prerequisites needed are having a modern version of windows i.e windows 10 or 11 and administarative privileges to install software
   

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   1. Extensions
   Click on the extentions view icon on the activity bar and install extentions necessary for your projects e.g prettier(code-formatter), live server, debugger, python debugger, pylance, code runnner for python etc
   2. Auto save
   Enable autosave to be able to save your files automatically
   3. File coding
   ensure your files are saved with UTF-8 encoding by default


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Activity bar- located at the far left, allows to switch between views such as explorer, search, run and debug and extensions
   Side bar- Displays different views and panels depending on the selected activity.
   Editor Group- The main area where you open and edit files. 
   Status bar- located at the bottom. Shows information about the current file such as encoding, line endings and language. It also displays eror and warning counts. 

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   A command pallet is where all the commands are found. It is important that your command names are labeled appropriately so users can easily find them. It can be accesed by pressing ctrl+shift+P or F1

   Common tasks
   -open files
   -change settings
   -run commands like git operations and various editor commands. 

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions enhance the functionality of VS code. They add support for new languages, debuggers and tools. 
   Users can find extentions by opening extention view and clicking the extentions icon on the activity bar or simply press ctrl+shift+x.
   search by extentions name or functionality and click install button for the desired extention.
   Examples: prettier, live server, debugger, python  debugger, codeium etc



6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   open the terminal by going to view, files then new terminal. The intergrated terminal allows you to run command-line operations within VS code. 
   Advantages 
   - its intergrated withthe vs which means you dont have to switch windows
   - directly interact with your projects files and settings.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   create file- rightclick in the explorer pane and select new file or new folder 
   open files- drag and drop files into the editor or use ctrl+o
   navigation- use ctrl+p to quickly open files by name, or use names on top of the editor to navigate directories

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   find and customize: go to files-preferences-settings
   change theme:search for "color theme" to switch themes
   change font size: search for "font size" to adjust
   change keybindings- go to files-preference-keyboard shortcuts

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   1. Setting up and starting debudding
   -open the file you want to debug
   -click on the run and debug icon in the activity bar
   -configure your launch.json file if prompted
   use breakpoints the watch window and debug console to control and inspect your program
   Key features
   breakpoints
   debug console
   watch
   call stack
   

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    1. initialize repository- open source control view and click initialize repository
    2. commit changes- stage changes by clicking the + icon them commit with a message
    3. Push changes to github-open the command panel, type git, add remote and enter the repository URL
    -push changes using git:push from command panel


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

