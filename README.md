[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15293601&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   -Head over to the Microsoft website. 
   -Use the URL provided above to download windows 11 on your preferred browser.
   -Be sure to check the system reqirements for installation. Use the 'PC Health Check' on the page header or you could opt to run your PC health checker app.  
   -If your device meets the requirements, click 'Download now' 
   -Once downloaded, accept the terms and conditions. 
   -Select your preferred language and edition. 
   -You should be having a USB flash drive of at least 8GB. Click the 'USB flash drive' then next. If you hadn't connected a flash drive, do so then refresh your drive list. 
   -When you see your drive, click next.
   -The lastest version of Windows will be installed, verified and will start creating your Windows 11 media on the USB flash drive.
   -Once done, you'll see that your USB flash drive is ready. 
   -Use the BIOS key set by your manufacturer to access BIOS.
   -Go to 'Boot' then select your USB drive which could be labeled 'Removable Devices'. Make your changes then press F10. Your USB flash drive will start to boot. 
   -If a windows setup flash screen pops, it means you're on the right track. Select your language, time and currency and input method. Click next.
   -Click 'Install Now'.
   -Accept terms and conditions. 
   -Choose whether to upgrade your windows or if you'd like a custom one.
   -If custom, make sure you select the correct drive and click next. 
   -PC will reboot and another window will pop up. Select the country you're from, your keyboard layout. Click next and wait for the updates.
   -Your PC may restart. 
   -Once it's back, name your device and set it up with options provided dpending on your prefrence. 
   - If you have a Microf=soft account, log in. If not, bypass it and click 'sign-in options' then click 'offline account'.
   -Name your device and set up a passowrd.
   -Configure the rest of the settings to your preference and you'll be done.
   -Check your settings. If any windows update is needed, do so.
   -You have your freshly installed Windows 11., 

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   -Use the URL provided above to install Visual Studio. 
   -Click the download option for your PC(Windows, Mac, ubuntu etc). 
   -Once the VS Code file is downloaded, click on it. 
   -Accept the agreement then click next. 
   -A default location for storage is selected. If you want to change it, do so. 
   -Start menu folder. Leave it as it is. 
   -Select your preferred additional tasks. All are advisable and convinient.
   -Click next then click install.
   -Once done, make sure the 'Launch Visual Studio Code' box is checked. and click finish.
   -Customise your settings. 
   -You can now work on your code. 

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   -Open your browser and search 'git download'
   -Open the fist link with url 'git-scm.com'
   -Click the 'Download for Windows' button.
   -Download the appropriate file for your PC. If not sure whether you PC is 32 or 64-bit, check your settings. 
   -Download the file.
   -Open the file and give it permissions by clicking Yes.
   -Click next on the Public liscence.
   -A default location for intallation is given. If you want to change, do so. If nit, click next. 
   -Select components window: Select your preferred choices.
   -Sart menu folder: Leave it as default which is often 'Git'
   -Click Next
   -Choose the default editor used by git. Select whichever editor tool you have such as notepad or vs code. Click Next
   -Select 'Let Git decide' on Adjusting the name of initial branch page.
   -Go with the recommended option on adjusting your path environment. Click Next
   -Go with default option on choosing the SSH excecutable. Click Next
   -Go with the default choice on Chooisng HTTPS transport backend. Click Next.
   -Go with the default choice on Configuring line ending conversations. Click Next.
   -Go with the default choice on Confuguring terminal emulator use with Git Bash. Click Next.
   -Go with the default choice on choosing the default behaviour of git pull. Click Next.
   -Go with the default choice on Credential helper. Click Next.
   -Go with the default choice on configuring extra options. Click Next.
   -You can select the optins in the configuring experimental options. If you do not wish to, don't. 
   -Click Install.
   -Select the Launch Git Bash and Click Finish. 
   -Open Git Bash.
   -Run the following command 'git --version' to confirm that you've installed git.
   -To configure your git to your local machine use the command 'git config --global user.name "Your Name"'. Run it
   -Run another command 'git config --user.email"Your email"'. 



   -Create a GitHub account using the URL provided above.
   -Use the email you used to configure git to your local machine.  

   -Your git and github are now set. 

   ->To create my repo
   -Go to github and create a repo. Mine is called sample-git-wk2assign.txt'
   -Open your Git Bash
   -Make a new directory named whatever you choose. In my case I already had one. To create a new one use the command 'mkdir filename'
   -Once you make that directory go into it using 'cd filename'. cd is change directory
   -Open your File Explorer and create a new file
   -run the command 'git init'
   -run the command 'git status' 
   -You will notice you have a file that has not been tracked 'untracked files' and is red in color.
   -add your file using the command 'git add sample-git-wk2assign'
   -run the g command 'git status'
   -You will notice that your file color has changed to green and has been termed 'changes to be committed'
   -pass a message to your repo wich will be termed as your commit. Mine is 'This is my first commit'
   -Go to github and copy your URL
   Come back to Git Bash
   -run the command 'git remote URL'
   -it's time to push your changes back to github
   -run the command 'git push -u origin (branch name)'
   -go back to github and refresh your page
   -you will notice the file/document you created is there. 


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  -Use the URL proded above to install python. 
   -Click on Download Python latest version. Make sure to download the correct Python for your PC. 
  -Open the downloaded file. 
  -Select the add to path option then click install now or customise installation. 
  -Check all boxes on Optional features. Click nect.
  -Advanced options. Make sure to select the 'install python for all users'. 
  -A default install location is set. If you want to change it, do so. 
  -Click Install.
  -Click on Yes on administrator previledges. 
  -After set up ic complete, click close.
  -To check whether it's succesfully been installed, open your command prompt and check for it's version by running this command 'python --version'. 
  -If it runs and shows you the version you installed, you're good to go. 

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   -Open your command prompt or git bash.
   -Check your python version.
   -Run the following command 'pip --version'. If it's not recognized install it.
   - Use the following URL to install the pip file https://bootstrap.pypa.io/get-pip.py
   -Save it into your preferred location on your PC. 
   -OPen your command prompt again and browse to the directory where your file has been installed. 
   -Once in it, run the command 'python get-pip.py'
   -The pip installation will start.
   -Add pip path to environment variables. 
   -To check if succesfully installed run the commands 'pip help' or 'pip --version' 
   -If installed well, the command will run properly. 


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   -Use the URL provided above to install MySQL. Click it.
   -You can also search MySQL download. Click the first link on your browser page. Scroll down and click 'MySQL Community Downloads' then click 'MySQL Installer for Windows'.
   -There are two files, download the larger one. 
   -Click 'No thanks, just start my download'
   -Open the file
   -Allow administrator previledges. 
   -Select 'Custom' setup type
   -Select the mysql server to be installed as well as the workbench. Click Next.
   -Click Execute.
   -Once status is complete, click next.
   -On Product Configuration, click next
   -Type and Networking: continue w default. Click Next
   -Authentication method: Click Next
   -Create your password
   -Windows Service: keep default
   -Server file permissions: Allow all
   -Apply Configuration: Click Execute button
   -Once done, click Finish
   -Product Configuration: Click Next
   -Installation Complete: Check the option for starting MySQL Woekbench after setup then click Finish. 
   -MySQL Workbench will launch. 
   -Setup is complete.
   -You can also check the mySQL version on the command line. 


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins: Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration. 

-I have installed VS Code as my text editor.
-VS Code supports various extensions for syntax highlighting, code formatting, linting and version control integration.
-The extensions I have so far are Python, Python Debugger, JavaScript,Flutter,Dart and Html Css support. 
- To add them, search them on vs code and install them.  

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

    ->Steps taken to set up my developer environment have been outlined above.  

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.
-Windows challenges: PC failing to install windows yet it's compatible. Go back and run your PC health app and ensure necessary settings are enabled. Do the installation again. 
-Python challenges: PATH not added. Can be done manually. Go to your python file, go into the file written bin. Copy its path. Create a path in your environment variables for it and that's done. 
-Pip challenges: PATH not added. Can also be done manually. Go to your pip file and into the bin folder, select its address and create a path for it in environment variables. 
-MySQL challenge: Workbench installation failed. You could install it manually or repeat the installation process again being keen to push workbench as you push SQL server. That way it will be part of the package.
-Git and GitHub challenges: These ones are mainly because I haven't understood the commands well. Solution is to keep practicing. 


#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
