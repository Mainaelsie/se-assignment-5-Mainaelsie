[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15252935&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
Prerequisites:
 Windows 11 operating system
 Internet connection
 Administrator privileges

Installation process:
 Visit the official VS Code download page:  https://code.visualstudio.com/download
 Scroll down and click the 'Download for windows' section.
 Once downloaded double click theinstaller file to launch the setup process.
 By default the location will be the C: drive but you can change by clicking 'Browse' and selecting a new folder.
 You can opt to install additional components if desired or leave out these options unchecked if you don't really need then at the moment.
 Click "Install" to start the instalation process.
 Once the instalation is complete click "Launch"  to start using VS Code.

You should be having the VS Code installed when done with these steps. There might be optional updates available during the instalation process but you can choose to install them or update later if need be.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

There are some basic configurations that can be adgusted like:
   Customizing the settings by going to 'file > preferences > settings'.
   Choosing a theme that you are comfortable with by going to 'file > preferences > color theme'.
   Setting your preferred font size.
Enhansing certain extensions like:
   Python: Provides rich support for the python language.
   ESLint: Identifies potential errors and code quality issues for JavaScript/TypeScript.
   Debuggers: Language specific deburgers to step through code and identify bugs.
   Bracket pair colorizer: Colorizes matching brackets to make it easier to identify code blocks.
Change the editor settings like:
   Enable auto save to avoid losing your work. to do this go to 'file > auto save'.
Customize the keyboard shortcuts by going to 'file > preferences > keyboard shortcut'.
Intergrate the version control eg: git. This is done to get seamless workflow. Ensure that you have the version control on your system.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

Activity bar:
   Located on the left side of the window.
   The purpose is to provide quick access to different sections of the VS Code, eg: File explorer, Git, Debug and Extentions enabling you to switch between features effectively.
   Allows you to navigate between different project file, open new folders and view recent files.      

Side Bar:
   Located next to the Activity bar, Typically on the right side.
   Offers context-specific views depending on the current workspace or open file.

   Contains various panels:
      - Explorer: Browse your project's file system, open files and create new files/folders
      - Search: Allows you to search within the codebase or within the current file.
      - Source Control: If git is intergrated, the side bar will also display Git secific views like the staged changes and commit history.
      - Extensions: Displays information about installed extensions.

Editor Group:
   This is the central area where code is written, editted and viewed.
   Contains multiple editor tabs each representing an open file. You can have multiple open and switch between them easily.
   Provides features like syntax highlighting, code completion and error highlighting.

Status Bar:
   Located at the bottom of the window.
   Displays the real-time information about the current workspace and project.

   Displays a number of things like:
      - Shows the current line and column position within the active file.
      - Displays details about the current selected text in the editor.
      - Shows the number of errors detected in the code.
      - Shows the CPU usage and memory consumption.
      - Shows the version control status of the curent file.
      - Shows the character encoding of the active file.
      - Indicates the programmimg language detected in the active file.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The command pallet is a powerful tool that provides quick access to many of the editor's commands. It allows you to execute commands and perform various tasks without having to navigate through menus or remember the keyboard shortcuts.

There are multiple ways to access the commad pallet:
   By using the keyboard shortcut. 'ctrl+shift+P'(on windows) and 'cmd+shift+P'(on macOS)
   Click on the 'Go To' menu option in the top menu bar and select 'Command Palette' from the dropdown.

NB: Before writing any command you mast start with '>' sign.

Examples of the common tasks that you can perform using the Command Pallette:
   Opening files:
      - '>Open file' quickly opens file in your workspace.
      - '>Recent files' access recently opened files.
   Searching and Replacing:
      - '>Find' perform a search within the current file.
      - '>Replace' replace text within the current file.
   Debugging:
      - '>Debug: Start Debugging' starts a debugging session.
      - '>Debug: Add Configuration' adds a debugging configuration.
   Settings and Preferences:
      - '>Preferences: Open Settings (UI)' opens the settings in UI mode.
      - '>Preferences: Open Keyboard Shorcuts' customizes keyboard shortcuts.
   Terminal:
      - '>Terminal: Create New Intergrated Terminal' opens a new terminal.
      - '>Terminal: Run Task' runs the predefined task.
   Extensions:
      - '>Extensions: Install Extensions' opens the extensions view.
      - '>Extensions: Disable' disables an extension.
   Git Commands:
      - '>Git: Clone' clones a repository.
      - '>Git: Commit' commits changes.
      - '>Git: Pull' pulls changes from a remote repository.
   Code Formatting and Refactoring:
      - '>Format Document' format the entire document.
      - '>Rename Symbol' renames all instances of a symbol.
   View and Editor Managment:
      - '>Toggle Sidebar' shows or hides the sidebar.
      - '>Split Editor' splits the editor into multiple views.
Benefits of using the Command Pallette:
   Quick access to commands without navigating menus.
   Consistency across all platforms.
   Find new actions and commands that you may not be aware.
   Focus on codding withour reaching for the mouse.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Role of extensions in VS Code:
   * Providing support for various Programming languages including syntax highlighting, autocompletion, linting and debugging. Example: Python, Java, C#.
   * Assist in managing and organizing projects, providing features like file explorer, task lists and project templates. Example: Project Manager, TODO Tree.
   * Provide advanced debugging capabilities  such as breakpoints, step-through execution and variable inspection. Examples: Debugger for chrome, Debugger for Node.JS, Jest, Mocha.
   * Provide in-editor documentation, code examples and learning resources to help developers understand and use various technologies. Examples: Markdown All in One, Rest Client.
   * Facilitate collaborations between team members by intergrating with version control systems and real-time collaboration tools. Examples: Live Share, GitHub Pull Requests and Issues.
   * Allows users to customize the look and feel of theier editor through themes and icon packs. Examples: One Dark Pro, Material Icon Theme.
   * Enable remote development capabilities, allowing developers to work on projects hosted in different environments such as servers, containers or virtual machines. Examples: Remote - SSH, Remote - Containers, Remote - WSL.
   * Help mainatain code quality by offering features like linters, formatters and static code analyzers whixh ensure consistent coding styles and help identify and fix potential issues early. Example: ESLint, Prettier, TSLint.
   * Boosts productivity by providing features like snippets, task runners and prohect templates which automate repetitive tasks and streamline common workflows. Examples: Code snippets for various languages, Task Runner, TODO Highlight.
   * Intergrate development tools and services directly into VS Code, streamlining the development process. Examples: Docker, GitLens npm Maven.

Finding, installing and managing extensions:
Extensions can be found on the VS Code Marketplace: https://marketplace.visualstudio.com/vscode 
To install an Extension you'll open the VS Code Marketplace, Browse or search for the desired extension and click 'Install'. VS Code will automatically download and install the extension.
The Extensions can be managed through the extension view in VS Code by clicking the Extension icon in the Activity Bar. View the installed Extension including their status, settings and commands then enable, disable or uninstall the extension as needed.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?


There are different ways to open the intergrated terminal in VS Code:
   Keyboard Shortcut: Press 'ctrl+' '(backtick)' on windows and Press 'cmd+' '(Backtick)' on macOS.
   Menu Option: Go to the top menu and select 'View' > 'Terminal'.
   Command palette: Press 'crtl+shift+P' to open Command palette then type 'Terminal: Create New Intergrated Terminal' and select it.

Operations to perform on the intergrated Terminal.
   Creating New Terminal: Click on the '+' icon 
   Switching bateween Terminals: Click on the terminal tabs or use the dropdown menu in the terminal tab bar.
   Splitting Terminals: Click the split terminal icon in the terminal bar which splits horizontally.
   Running Commands: You can run any command supported by your shell.
   Customize Shells: Go to 'file' > 'Preferences' > 'Settings' and search for 'terminal.integrated.shell' . You can set it to use Bash, PowerShell, Command Prompt or any other shell you prefer.

Advantages of using the Integrated Terminal over External terminal:
   It is easily accesible within your development environment, eliminating the need to switch between multiple windows or applications.
   It has access to the current project's context, making it easier to run commands and tasks related to the project.
   It stores a history of previously executed commands, allowing you to quickly recall and re-run them.
   It frequently provide features which enhance the user experience and improve productivity.
   Many allow for customization providing a tailored experience.
   It allows for quick navigation within the project's codebase and provide the ability to execute code snippets directly from the terminal.
   Automated tasks and scripts can be easily executed from the integrated terminal, reducing manual effort and improving efficiency.
   Facilitate easy access to debugging tools and provide a convenient environment for troubleshooting issues within the project.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

To create new folder and file :
   File: Press 'ctrl+N' to open new file
   Folder: Right click on the file explorer and select new folder.
To open Files and folders:
   File: Open file explorer and double-click the file you want to open.
   Folder: Couble click the folder you want to open in the file explorer.
Managing Files and Folders:
   To rename right click the file/folder and select 'Rename' then wrote the name you wold like.
   To Move/Copy drag and drop the file/folder to the desired location.
   To delete select the file/folder and press 'Delete'
Navigating between files and directories:
   File Explorer:
      The file explorer provides a tree view of the current workspace. Expand or collapse folders to locate files.
   Command Palette:
      Press 'ctrl+P' to open the command palette then type '>File: Open Folder' and select the desired file/folder.
   Go to file: 
      Right click on the editor and select 'Go To File'. Enter the name or path of the file you want to open.
   Quick Open:
      Press 'ctrl+P' and type a few characters of the file/folder to filtey the results.
   

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

You can find the customize settings through the following methods:
   Open setting file 'file > preferences > Settings' to view and edit settings in a text format.
   Use the Settings Editor 'File > Preferences > Settings' to visually browse and modify settings.
   Press 'ctrl+Comma' to open the settings panel.
To change the theme navigate to 'Appearance > Colour theme' and select the desired theme or Add '"workbench.colorTheme": "<theme name>"' to the settings file.
To change the font size navigate to 'Appearance > Font' and adjust font size using the fomt size slider or rather add '"editor.fontSize": <font size>' to the settings file.
To change the keybindings navigate to keyboard shortcut and search for desired keybinding and modify the key combination or create a new one or rather just add '"keybindings.json":{"key": "<key combination>", "command": "<command name>"}' to the settings file.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

To debug a simple program you first have to install a debugger Extension then open a project containing the code you want to debug in VS Code. Place breakpoints at specific line of code to pause execution there. T start debugging press F5. Finally use the debug pane to step through the code line by line, pause on breakpoints and inspect variables.

Key debuggung features:
   Set breakpoints and conditional breakpoints to pause on specific conditions.
   Hover over variables to inspect their values and types during debugging
   Add watches to track the values of specific variables over time.
   Dubug applications running on remote machines or containers.
   Enhance debugging with extensions like the debugger for chrome and python visual debugger.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Initialize a Repository:
   Open the VS Code Command Palette (Ctrl+Shift+P on Windows/Mac, Cmd+Shift+P on macOS).
   Type "Git: Initialize Repository" and select the option.
   A new ".git" folder will be created in your project directory.

Making Commits:
   In the "Source Control" view, select the staged files.
   Click the "Commit" button or use the keyboard shortcut (Ctrl+Enter on Windows/Mac, Cmd+Enter on macOS).
   Enter a concise and meaningful commit message and click "Commit".

Pushing Changes to GitHub:
   Expand the "Extensions" panel on the left side of VS Code and click on the "GitHub Pull Requests" extension.
   Click the "Sign In to GitHub" button.
   Once authenticated, the "Publish Branch" button will become available.
   Click "Publish Branch" and select a remote repository to push to.
   If the repository does not exist, you can click "Create New" and enter a repository name.
   Enter a branch name (usually "main" or "master") and click "Publish Branch".
Your local changes will now be pushed to the specified GitHub repository.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

