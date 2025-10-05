Assuming you read the README.md file of this repository, this file is the detailed documentation of the overview listed in that file.
Here is how you set up your own VS code + Github project:
## How to create a folder, open it in VS Code, and Connect to GitHub
**Setting up a New Project and GitHub Repository**
### Creating a folder on your computer
1. Open **Command Prompt** (Windows +R-> type:cmd->Enter).
2. Navigate to where you want your project to be.

    - If your command prompt looks like this:

       *Microsoft Windows [Version 10.0.22621.4317] (c) Microsoft Corporation. All rights reserved.*

      Paste the **Location** you want the folder to be in. You can also do this by right clicking anywhere you want it to be->`Properties`->`Location`-> Copy then paste it in the command prompt and hit *Enter*.
   - If  your command prompt also includes:

     **C:\Users\DELL>** or something similar, then you need to change the directory to where you want your project to be. You can do this by typing the `cd path` where path is the location you want your project to be. Type
   `cd /d C:\Location of the path` and hit *Enter*.
3. Create your folder by typing `mkdir` **"foldername"** (you can name it whatever you want) and hit Enter. Then enter `cd foldername` to go in that folder.
4. Open the folder in VS Code by typing `code .` and enter. This will open VS Code with the folder you just created.
5. In VS Code, touch the `foldername` in the Explorer tab and press on *New file* icon to create a **README.md** file for an Overview on what the repository is about and to also create a **main/note.md** file for writing long notes or documentation.
6. Start writing in the  README.md or the note.md file using Markdown Syntax. Visit my detailed Markdown guide here: 👉[Markdown Syntax Guide](https://github.com/Jjirel/markdown-syntax-guide.git) for basic syntax, tips and examples.

### Initializing Git and Setting up User Info
1. Open the **Terminal** in VS code(**CTRL+ `**) & initialize Git for this folder by: