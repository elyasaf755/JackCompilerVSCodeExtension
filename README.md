# A Jack Compiler Extension For Visual Studio Code
A **Save & Compile** button for Jack programming in Visual Studio Code

# Prerequisites
1. Download and install [Power Tools](https://marketplace.visualstudio.com/items?itemName=ego-digital.vscode-powertools) and [macros](https://marketplace.visualstudio.com/items?itemName=geddski.macros) extensions for VS Code.<br>
2. Download and install [Java](https://www.java.com/en/download/manual.jsp). Make sure Java is added to PATH.
<br>

# Installation:<br>
Download [this](https://drive.google.com/file/d/1tNN7n-I-4-8r0CG-_JELqLHNmVWI8b0Q/view?usp=sharing) .rar file, and extract its contents into your Jack project's folder.<br>
After that, your Jack project's folder should have a **.vscode** folder, like shown here:<br>
![](https://github.com/elyasaf755/JackCompilerVSCodeExtension/blob/master/images/Jack%20project's%20folder.png?raw=true)
<br>
<br>
# Usage:<br>
Open your Jack project using VSCode by clicking **File -> Open Folder...** and then selecting your Jack project's folder.<br>
After a few seconds of VSCode loading your project, you'll notice a small **Save & Compile** button at the bottom-left corner of the IDE:<br>
<br>
![](https://github.com/elyasaf755/JackCompilerVSCodeExtension/blob/master/images/Save%20&%20Compile.png?raw=true)<br>
<br>
<br>
<br>
Clicking the **Save & Compile** button will save your entire project and will try to compile it. If the compiler encountered errors, it will pop-up error messages. Clicking each error message will redirect you to the problematic line of code in a specific file (problematic - by the compiler's prespective):<br>
<br>
![](https://github.com/elyasaf755/JackCompilerVSCodeExtension/blob/master/images/InkedGo%20To%20File_LI.jpg?raw=true)<br>
<br>
<br>
If compilation was succesful - the following message will pop-up:<br>
<br>
![](https://github.com/elyasaf755/JackCompilerVSCodeExtension/blob/master/images/Succes.png?raw=true)<br>
<br>
<br>
### Notes:<br>
As for now, you need to repeat these steps for each Jack project you create if you want to enjoy this functionality.<br>
A Jack project's folder that doesn't have this specific **.vscode** folder in it - won't be able to be compiled in VS Code like described above.<br>
<br>
The [Nand2Tetris - Jack Language Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=amadeann.jack-language-syntax-highlighting) extension is extemely recommended.
<br>
<br>
### Contact:<br>
If you have any questions, you can send me an email to **elyasaf755@gmail.com**
