Defining features

There is no exact specification of what a portable application is, but the following list contain the properties that are usually assumed when talking about portable software:

1. No installation. The program is delivered in a zip archive that you only need to extract into a folder of your choice (the “program folder” below) to “install” the program. (无须安装)

2. This program folder contains everything needed to run the application. No files need to be installed on the host computer first. The exception to this are common runtime files, such as .Net, Java and Visual Basic runtimes, that are usually already installed and in a sense can be seen as part of the runtime environment that everyone already have. (程序目录包含一切)
All application settings are saved inside the program folder. Thus if the program folder is moved, settings come along too. (配置也保存程序目录）

3. The application does not save or change anything on the host computer outside its program folder. This includes the Windows registry.（程序不会动自己目录之外的任何东西)
