[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271635&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.


Answer to the Assignment : Setting up your Development Environments

No 1: Select Your Operating System (OS): Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11Step-by-step guide to download and install Windows 11. 
1. Check System Requirements:
Ensure your PC meets the minimum system requirements for Windows 11:
- 1 GHz or faster with at least 2 cores on a compatible 64-bit processor or SoC
- 4 GB RAM
- 64 GB or larger storage device
- UEFI, Secure Boot capable
- TPM version 2.0
- DirectX 12 compatible graphics / WDDM 2.x
- 9” with HD Resolution (720p)
- Internet connection (for updates and features)
 2. Backup Your Data:
Before proceeding, back up your important files and data.
3. Download Windows 11:
1. Go to **Settings > Update & Security > Windows Update**.
2. Click on **Check for updates**.
3. If Windows 11 is available, you’ll see an option to download and install.
4. Install Windows 11:
Using Windows Update or Installation Assistant
1. Follow the prompts to download and install Windows 11 directly on your PC.
2. Your PC will restart several times during the installation process.
Using Installation Media
1. Insert the bootable USB drive or DVD into your PC.
2. Restart your PC and boot from the USB drive/DVD.
   - You might need to change the boot order in your BIOS/UEFI settings.
3. Follow the on-screen instructions to install Windows 11.

5. Post-Installation:
1. Complete the initial setup process, including signing in with a Microsoft account.
2. Check for any updates via **Settings > Update & Security > Windows Update**.
3. Reinstall your applications and restore your backed-up data.
Additional Tips:
- Ensure your PC's BIOS/UEFI is up to date.
- Have your Windows 10 license key ready, just in case it's required during installation.
- Disconnect non-essential peripherals during installation to avoid compatibility issues.
Following these steps will help you successfully download and install Windows 11 on your PC.


No 2: 
Download and Install Visual Studio Code
Your IT administrator might point you to a specific location from which to install Visual Studio.
Step 3 - Initiate the installation
If you downloaded a bootstrapper file, you can use it to install Visual Studio. You need administrator permissions. The bootstrapper installs the latest version of the Visual Studio Installer. The installer is a separate program that provides everything you need to both install and customize Visual Studio.

From your Downloads folder, double-click the bootstrapper named VisualStudioSetup.exe or named something like vs_community.exe to start the installation.

If you receive a User Account Control notice, choose Yes. The dialog box asks you to acknowledge the Microsoft License Terms and the Microsoft Privacy Statement. Choose Continue.



Step 4 - Choose workloads
After you install the Visual Studio Installer, you can use it to customize your installation by selecting the feature sets, or workloads, that you want. Here's how.

Select the workload that you want in the Visual Studio Installer






Review the workload summaries to decide which workload supports the features you need. For example, choose the ASP.NET and web development workload to edit ASP.NET Web pages with Web Live Preview or build responsive web apps with Blazor. You might choose from the Desktop & Mobile workloads to develop cross-platform apps with C#, or C++ projects that target C++20.
After you choose the workloads that you want, select Install.
Next, status screens appear that show the progress of your Visual Studio installation.
 Tip
At any time after installation, you can install workloads or components that you didn't install initially. If you have Visual Studio open, go to Tools > Get Tools and Features, which opens the Visual Studio Installer. Or, open the Visual Studio Installer from the Start menu. From there, you can choose the workloads or components that you wish to install. Then, choose Modify.
Step 5 - Choose individual components (optional)
If you don't want to use the Workloads feature to customize your Visual Studio installation, or you want to add more components than a workload installs, you can install or add individual components from the Individual components tab. Choose what you want, and then follow the prompts.




Step 6 – Install language packs (optional)
By default, the installer program tries to match the language of the operating system when it runs for the first time. To install Visual Studio in a language of your choosing, choose the Language packs tab from the Visual Studio Installer, and then follow the prompts.


Change the installer language from the command line
Another way that you can change the default language is by running the installer from the command line. For example, you can force the installer to run in English by using the following command:
vs_installer.exe --locale en-US
The installer remembers this setting when you run it again. The installer supports these language locales: zh-cn, zh-tw, cs-cz, en-us, es-es, fr-fr, de-de, it-it, ja-jp, ko-kr, pl-pl, pt-br, ru-ru, and tr-tr.

Step 7 – Select the installation location (optional)
You can reduce the installation footprint of Visual Studio on your system drive. For more information, see Select installation locations.


Step 8 - Start developing
After installation is complete, you can get started developing with Visual Studio.
Select the Launch button.
On the start window, choose Create a new project.

In the template search box, enter the type of app you want to create to see a list of available templates. The list of templates depends on the workloads that you chose during installation. To see different templates, choose different workloads.
You can also filter your search for a specific programming language by using the Language dropdown list. You can filter by using the Platform list and the Project type list, too.
Select Next. Provide other information in the following dialog boxes, and then select Create.
Visual Studio opens your new project, and you're ready to code!S







No 6: How to Install and Configure MySQL on a Windows Server
Introduction
MySQL is a well-established relational database management system. It is fully compatible with a Windows computer system. By using the MySQL Installer, an application designed to simplify the setup of MySQL products, MySQL can be installed and deployed within minutes. 
Prerequisites
•	Administrator privileges on Windows server
•	Windows computer system
Download MySQL Installer for Windows
The MySQL Installer for Windows helps you control the installation process by providing a user-friendly interface. It also guides you through the steps needed to configure MySQL.
Access your Windows server and download the MySQL Installer. A free Community edition MySQL Installer is available from the official page: https://dev.mysql.com/downloads/installer/
You are given the option to download either the Web Community version or the Full MySQL package.
•	The Web version (A) contains only the MySQL Installer and configuration files. You can customize and add additional MySQL products at a later point.
•	The Full version (B) contains all MySQL Windows products, including the MySQL Server.
Select and download your preferred version. In this example, we selected the Full MySQL Package (B).
 
After selecting a version, you are provided with the option of signing up for a MySQL Community account. If you are not interested, select the No thanks, just start my download option at the bottom of the page.
 
By selecting this option, the download process starts immediately. Once the download is complete, you can execute the MySQL Installer file from the download folder.
It can take a few moments while Windows configures the MySQL Installer and prepares the installation and configuration process.
Set Up MySQL Installer for Windows
After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.
Note: Preconfigured setups can be customized later if necessary.
After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.
•	Developer Default installs all the tools you need to develop and micromanage your MySQL databases effectively.
•	Server Only is used to install an instance of the MySQL Server and forgo other MySQL products.
•	Client Only installs all products except the MySQL Server and associated tools.
•	The Full configuration installs all available MySQL products.
A Custom setup allows you to select the individual elements that are to be installed and alter predefined default settings.
In the example below, we select the Server Only option and click Next.
 
At this point, the system tries to resolve possible inconsistencies. It might inform you that additional packages need to be installed for the process to continue (e.g., Microsoft Visual C++ 2019 Redistributable Package). You can also run into Path installation inconsistencies if you have previous MySQL installations on your Windows Server.
Luckily the MySQL Installer auto-resolves issues and installs the latest binary compatible version of missing software. You are now ready to start the installation process in earnest. Click Execute to begin the installation process.
 
Once the status of the installation status is labeled as Complete, you are ready to configure the MySQL database.
Configure MySQL Server on Windows
The MySQL Server 8.0.19 is now ready to be configured. Initiate the process by clicking Next.
 
1. High Availability
The first configuration option affects database availability. It allows you to decide if you want to set up a Standalone MySQL Server or an InnoDB server cluster to improve availability. In this instance, we selected the classic, single server option.
 
2. Type and Networking
The Type and Networking section is used to define several essential features.
The Config Type option lets you choose between three server configuration types. Development Computer, Server Computer, and Dedicated Computer define whether the server is dedicated solely to running your MySQL database or is going to share the underlying system with other applications.
In this example, we decided to create a dedicated MySQL server.
 
The Type and Networking tab can also define the port the MySQL server is listening on. The default setting is port number 3306 and can be changed to suit your needs.
By checking the Show Advanced and Logging Option box, you can set additional logging options at a later stage.
Click Next once you’ve selected the options you feel meet your requirements.
 
3. Authentication Method
It is possible to choose between two authentication methods, the recommended Strong Password Encryption, and the Legacy Authentication Method. Select the recommended Use Strong Password Authentication option.
 
4. Accounts and Roles
You are now prompted to enter a password for your MySQL root user. You can also create additional roles for various users and purposes.
This is only an initial setup, and credentials can be edited once the installation is complete.
 
5. Windows Service
By defining MySQL as a Windows Service, it can now start automatically whenever the Windows system boots.
If you decide to start MySQL as an executable application, you would need to configure it manually.
 
6. Logging Options (Optional)
If you have selected the Show Advanced Logging option in the Type and Networking tab, you are now able to set up MySQL log preferences.
Logging options let you select the types of logs you want to activate and define the log directories.
 
Click Next to reach the Advanced Options section.
7. Advanced Options (Optional)
Advanced Options include setting a unique server identifier, and the type of case (Lower/Upper) to be used for Table Names.
These settings are only available if you have checked the Show Advanced Options box in the Type and Networking tab.
8. Apply Configuration
You have successfully configured the MySQL server and need to confirm for the MySQL Installer to apply the configuration.
An overview of the configurations steps appears on the screen. Click Execute to apply the configuration.
 
The system informs once the configuration process is completed. Select Next to continue the installation process.
 
Complete MySQL Installation on Windows Server
After clicking Next, you are given the option to copy the installation process log to the Windows Clipboard.

 
Click Finish to complete the MySQL server installation on Windows.
Start MySQL Server on Windows
If you need to start the MySQL Server on Windows for the first time enter the following command in the Windows Command Prompt:
"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console
The path in this command is the default installation folder. In case you have installed MySQL in a different folder, the command needs to reflect that to launch the mysqld executable file successfully.
The --console option displays output directly on your console. Omitting this option sends the output directly to the MySQL logs.
Stop MySQL Server on Windows
To shut down MySQL Server in Windows, type the following command in the Windows Command Prompt:
"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqladmin" -u root shutdown
The mysqladmin tool performs the shutdown command and fully stops the MySQL server. The system does not provide output as confirmation.
Conclusion
Installing MySQL on a Windows server is simple when using the MySQL Installer tool. The configuration process has many available options that are significantly easier to navigate by following the stages outlined in this article.
The same methods can be used to install various MySQL products as well as alter existing configurations at a later point. One of those products is Microsofts SQL Server Express, a free version of Microsoft’s SQL Server.

