## Description
A very generic template to create CPL files that execute code from within Windows Control Panel (control.exe). This XLL will only open a MessageBox but the code can easily be adapted if you need it to do something else like spawning a child process if you want to improve your detection rules.

## Usage
Compile the code in main.c (e.g. in Visual Studio) as DLL. Rename the resulting DLL into filename.cpl and it should automatically open when doubleclicked. 
