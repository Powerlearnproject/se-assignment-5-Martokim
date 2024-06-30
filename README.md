[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15322521&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

     step1. Download visual Studio Code :
       Open your browser and visit https://code.visualstudio.com/
        click on the download for windows button 
     Step 2.Run the installer :
       Locate the downloade installer file and double-click it to run the setup 
     Step 3. Installation process :
      - In the Visual Studio Code Setup wizard, read and accept the license agreement, then click "Next".
      - Choose the destination location where you want to install Visual Studio Code or leave it as the default location, then click "Next".
      - Select the additional tasks you would like to perform, such as create desktop icon.
      - Click "Next" after selecting your preferences.
      - Click "Install" to begin the installation.
      - Once the installation is complete, click "Finish". You can optionally choose to launch Visual Studio Code immediately by checking the box.
     Step 4. Launching VS Code:
     - Open the Start menu and type "Visual Studio Code" to search for the application.
     - Click on the "Visual Studio Code" icon to launch the application.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing Visual Studio Code , you can adjust severel settings and install extensions to create an optimal coding envireonment 
   i. Theme :
    - Go to 'File > Preferences > Color Theme or press Ctrl+K Ctrl+T.
    - Choose a theme that you find visually comfortable. Popular themes include "Dark+" (default dark), "Light+" (default light), and "Monokai".
   ii. Font Setting:
    - Open settings via File > Preferences > Settings or press Ctrl+,.
    - Open settings via File > Preferences > Settings or press Ctrl+,.
    - Search for "font size" to adjust the font size for readability.
   iii. Editor Settings:
    - Configure settings like:
         Tab Size: Set the number of spaces for a tab ("editor.tabSize": 2).
         Auto Save: Enable auto-saving of files ("files.autoSave": "afterDelay").
         Word Wrap: Enable word wrap to avoid horizontal scrolling ("editor.wordWrap": "on"). 

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
        
   Activity Bar : Provides access to different views and functions, such as Explorer, Search, Source Control, Run and Debug, and Extensions.
   Side Bar :Displays different views and tools depending on the selected activity.Views such as search , Explorer , Source control , Run and debug and extensions
   Editor Group : Contains the main editing area where you can open multiple files or folders for editing.
   Status Bar : Displays information about the current state of the editor, such as the current file path.
   

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette is a tool that allows you to quickly access commands and features in VS Code.You can access the command palette using the keyboard shortcut 'ctrl+shift+p' .
   Common tasks that can be performed using the command palleta include : 
   - Opening files 
   - Searching for files
   - Running commands.
   - Changing Settings.
   - Installing extensions.
   - Debbuging.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
    
    - The role of extensions in Vs code include :
     > Enhance Specific programmin languages such as syntax highlighting , code completion, linters, and debuggers tailored to various langueges like python , javascript , java and more 
     > Improve code editing experience with feature like code formatting, snippets, bracket matching, and keyboard shortcuts.
     > Intergrate with development tools such as Git, version control systems , task runners and debuggers for a streamlined workflow.
     > Add theming and customization such as fonts, and layouts to fit your code preferences.
     > Expand functionality for specific tasks like web development , testing, testing and datebase management .
   - Finding ,Installing and Managing Extensions 
     > Click the Extensions icon (puzzle piece) in the Activity bar on the left, or use the shortcut Ctrl+Shift+X
     > Explore the curated categories or use the search bar to find extensions by name or functionality.
     >  Click the "Install" button for the desired extension. You can manage installed extensions, view details, disable, or uninstall them from the Extensions view.
   - Essential Extensions for Web Development 
    > HTML CSS Support: Provides CSS class and ID name completion for HTML files.
    > Bracket Pair Colorizer: Colors matching brackets to make it easier to identify corresponding pairs.
    > GitLens: Enhances Git capabilities in VS Code, providing features like blame annotations, repository status, and detailed commit information.
    > JavaScript (ES6) Code Snippets: Provides snippets for common JavaScript patterns and functions.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   - How to open intergrated terminal : navigate to the top bar menue , click on 'Terminal ',select 'NewTerminal'.
   - how to use the intergrate terminal : 
     > You can use basic shell commands (like 'ls' , 'cd','mkdir' , etc )
     > Intergrated tasks (like build or test tasks) can be executed directly in the terminal. Define tasks in the tasks.json file and run them using Terminal: Run Task from the Command Palette.
     > Open multiple terminals by clicking the + icon in the terminal tab or using the shortcut Ctrl + Shift + Win key.
     > Split the terminal view by clicking the split terminal icon or using the command Terminal: Split Terminal.
     > Use the dropdown menu in the terminal tab to switch between different terminal instances.
   - Advantages of Using the Integrated Terminal Compared to an External Terminal 
     > Seamless Integration: The integrated terminal is part of the VS Code interface, allowing developers to work within a single environment without switching context.
     > Productivity and Efficiency:
       ~ Easily open, close, and switch between terminals without leaving the editor.
       ~Manage multiple terminals in a single interface, facilitating tasks like running a server and watching files simultaneously.
     > Customization and Configuration:
       ~ The terminal can match the VS Code theme, providing a consistent visual experience.
       ~ Configure the terminal to use your preferred shell (e.g., Bash, PowerShell, Zsh) and customize it to fit your workflow.
       ~ The integrated terminal shares environment variables with the editor, making it easier to manage and debug environment-specific issues.
     > Additional Features: 
      ~ The terminal can work alongside the debugging tools in VS Code, allowing for a more cohesive debugging experience.
      ~ Integrated accessibility features in VS Code apply to the terminal as well, making it easier for users with disabilities to work within the environment. 

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
 
   - How to create a File : 
    ~ Right-click on the folder where you want to create the file in the Explorer pane.
   ~ Select New File and enter the file name.

  - How to create a Folder:
   ~ Right-click on the parent directory in the Explorer pane.
   ~ Select New Folder and enter the folder name.

  - Opening Files and Folders:
   ~ Navigate to the desired file or folder and click on it to open it in the editor.

  - Managing Files and Folders :
   ~ Renaming:Right-click on the file or folder in the Explorer pane and select Rename.
   ~ Deleting:Right-click on the file or folder in the Explorer pane and select Delete.
   ~ Moving: Use cut (Ctrl + X) and paste (Ctrl + V) commands to move files and folders.

  - Navigating Between Different Files and Directories Effeciently :
   ~ Explorer Pane: The Explorer pane provides a hierarchical view of the workspace, allowing for easy navigation between files and folders.
   ~ Quick Open: Press Ctrl + P (Windows/Linux) or Cmd + P (macOS) to open the Quick Open dialog.
   ~ File Tabs:Open files are displayed in tabs at the top of the editor. Click on a tab to switch between open files.
   ~ Keyboard Shortcuts: 
      Go to File 'ctrl + p to quickly open files.
      Navigate Back/Forward: 'Ctrl + - and Ctrl + Shift + - '
      Go to Definition: F12 to go to the definition of a symbol.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   - Settings icon : select 'Settings'
   - Command Palette: Type Preferences: Open Settings and select it.
   - Menu Bar:Navigate to File > Preferences > Settings
   - Changing the Theme :
     ~ Settings UI : Open settins . In the search bar, type 'theme', Click on 'color theme ' and select a them from the list.
     ~ Command pallet : Open the command palette using 'ctrl + shift + p' , Type 'Preferences : color theme" and select it  , choose a theme from the list.
   - Changing the Font Size 
    ~ Open the settings, in the search bar, type 'font size' , Locate the 'Editor : Font size ' 
   - Changing keybindings 
    ~ In the Keyboard Shortcuts UI, search for the command you want to change , Click on the pencil icon next to the command , Press the desired key combination.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   - Open the Debug View:Click on the Debug icon in the Activity Bar on the side of the window.
   - Create a Debug Configuration:Click on the gear icon at the top of the Debug view to open the launch.json file. If no configuration exists, VS Code will prompt you to create one , Select the environment you are working with (e.g., Node.js, Python, etc.). This will generate a launch.json file with default settings.
   - Set Breakpoints: Open the file you want to debug , Click in the gutter next to the line number where you want to set a breakpoint. A red dot will appear indicating the breakpoint.
   - Start Debugging:In the Debug view, select the configuration you created from the dropdown menu , Click the green play button (Start Debugging) or press F5 to start debugging.

   - Key Debugging Features in VS Code:
    ~ Breakpoints: Set breakpoints by clicking in the gutter next to the line number,
     Conditional Breakpoints: Right-click on a breakpoint and select Edit Breakpoint to set conditions (e.g., hit count, expressions).
    ~ Watch Expressions: Add variables or expressions to the Watch panel to monitor their values during debugging.
    ~ Call Stack: View the call stack to understand the execution flow of your program. It shows the sequence of function calls that led to the current breakpoint.
    ~ Variable Inspection: Inspect variables in the Variables panel. You can expand objects to see their properties and values.
    ~ Debug Console: Use the Debug Console to evaluate expressions, execute commands, and interact with the running program.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   
    - Integrating Git with VS Code for Version Control:
     ~Ensure Git is installed on your system
     ~ Set up your Git configuration , if not already done by doin the following : 
         git config --global user.name "Your Name"
         git config --global user.email "your.email@example.com" 

    - Initializing a Repository: 
     ~ Open your project folder using File > Open Folder or Ctrl + K, Ctrl + O
     ~ Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl + Shift + G
     ~ Click on Initialize Repository.
     ~ VS Code will initialize a Git repository in your project folder and display the changes.
   - Making Commits:
    ~ In the Source Control view, you will see a list of files that have been modified.
    ~ Hover over the file you want to stage and click the + icon that appears to stage individual files.
   - Commit Changes: 
    ~ After staging the changes, enter a commit message in the message box at the top of the Source Control view.
    ~ Press 'ctrl + Enter '.
   - Add Remote Repository:
    ~ Add Remote Repository:Open the terminal in VS Code Ctrl +  , Add the remote repository: eg git remote add remote origin https://github.com /martokim/newRepo.git 
   - Push Changes: git push -u origin master .

   The following are the sources and references used in the answers :
   ~ Visual Studio Code Documentation: The official documentation provides comprehensive guides and tutorials for using all features of VS Code, including the Command Palette, User Interface, and setup configurations. https://code.visualstudio.com/docs

   ~ VS Code Git Integration: Detailed information on integrating Git with VS Code can be found in the documentation. https://code.visualstudio.com/docs/editor/versioncontrol

   ~ Installation Instructions for VS Code: The official download page provides installation instructions for various operating systems, including Windows. https://code.visualstudio.com/Download

   ~ VS Code First-time Setup: Guides and recommendations for initial configurations and settings are available in the documentation and community forums. https://code.visualstudio.com/docs/setup/setup-overview

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

