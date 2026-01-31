# Vertex Monorepo
This is a Mega repository of the entire VertexEngine SDK, this is a giant project.

## Help
The documentation is in the following link:
[https://vertexenginedocs.netlify.app/](https://vertexenginedocs.netlify.app/) for help.

## How to install Pyinstaller
Step 1. Type in:
pip install pyinstaller

Step 2. Wait a few min, don't worry if it takes 1 hr or more, it will finish

Step 3. How to use pyinstaller
type:
python -m PyInstaller --onefile *.py

There are flags:
--noconsole > disables the console when you run the app
--onefile > compress all of the code into one file
--icon > the *.ico file after you type it will be set as the app icon.

## Packages
### VertexEngine
This is the main part of the Vertex Monorepo. It is the core of VertexEngine, it has all the core libraries down to the UI and GUI.

### VertexEngine-WebEngine
This is the WebEngine of VertexEngine. This handles the HTML, CSS, JS. It provides JSBridge and recomended to pair with PyQt6's WebEngine. This can help load Websites.

### VertexEngine-CLI
CLI means Command Line Interface. It provides you with commands that help you make VertexEngine Applications. It's currently going to be actively updated, expect a lot of content!

## Core Dependencies
Vertex obviously has heavy dependencies since it's a game engine, the following requirements are:

| Dependency       | Version                              |
|------------------|--------------------------------------|
| PyQt6            | >=6.7                                |   
| Pygame           | >=2.0                                |
| Python           | >=3.10                               |

## About Me
I Am a solo developer in Diliman, Quezon City that makes things for fun :)
77 Rd 1, 53 Rd 3 Bg-Asa QC
Email:
FinalFacility0828@gmail.com

## 📄 License
VertexEngine/Vertex is Managed by the MIT License. This license allows others to tweak the code. However, Attributions are required as said in the license. Check LICENSE file for more details.
