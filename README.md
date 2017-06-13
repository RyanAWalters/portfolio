# Portfolio

An index of all of my work that is on GitHub. Many, many more to come! *Click on the name of any project to be taken to its GitHub page.*

**All programs marked with a check mark (:white_check_mark:) are complete, released software programs.**

## Index:
 * ### **[Large Team Projects](#large-team-projects)**
   * **:white_check_mark: [Fantasy World Manager](#white_check_mark-fantasy-world-manager)**
   * **[Unreal Graphics Project](#unreal-graphics-project)**
   * **[Unreal Python Sudoku Solver](#unreal-python-sudoku-solver)**
 * ### **[Large Personal Projects](#large-personal-projects)**
   * **:white_check_mark: [Puxxle (Mobile Game)](#white_check_mark-puxxle-mobile-game)**
 * ### **[Personal Projects](#personal-projects)**
   * **:white_check_mark: [Power of 2 Image Resizer - Game Engine Texture Optimization](#white_check_mark-power-of-2-image-resizer---game-engine-texture-optimization)**
   * **[Simple Python 3D Graphics Rendering Engine](#simple-python-3d-graphics-rendering-engine)**
   * **[Advanced Python Lighting Model](#advanced-python-lighting-model)**
 * ### **[Smaller Assignments](#smaller-assignments)**
   * **[Dimes and Quarters Problem - Optimal Solution Finder](#dimes-and-quarters-problem---optimal-solution-finder)**
   * **[Simple pl/0 Compiler](#simple-pl0-compiler)**

---


# Large Team Projects

## :white_check_mark: [Fantasy World Manager](https://github.com/ForJ-Latech/fwm)
> 
> Fantasy World Manager is a program that serves as a Dungeon Master's tool in any tabletop RPG, like Dungeons and Dragons. It allows the Dungeon Master to create, edit, search, and view a database of places, characters, groups, events, gods, etc. on the fly while playing the game. Assign images and sounds to any of the aforementioned entities and allow the players to use their phone to explore the world the Dungeon Master has created.
>
> ***This project was created by a small team of agile developers, including a scrum master. We used JIRA to create, assign, and track our user stories. It is written in Java and uses JavaFX for the GUI and Jetty for the web service. We used SVN and Git for version control and Eclipse as our standardized development environment***
> 
> **I was responsible for the UI and the classes that comprise it, such as the list view that searches the database, as well as the relationship links (and both of their underlying functionalities). I also extended the built in ImageView class to allow the user to drag and drop images to attach them to the entity (person, place, etc.) and save them in the database. My class can also grab images out of HTML links (like, for instance, the Google logo link), so the user can drag images from their browser straight onto an entity in the program. This was achieved by using look-back regular expressions to extract the image source from the raw HTML.**
>

## [Unreal Graphics Project](https://github.com/RyanAWalters/UnrealGraphicsProject)
>
> This project is a 3D action game demo where the player must survive onslaughts of enemies. Luckily there are allies to aid you on your mission to scale the mountain and defeat the final boss. All you have is a sword and super-human agility.
> 
> This game demo was created by myself and one other person in the span of 2.5 months as a side project in a class. It was created in Unreal Engine, and we used Git for version control.
>
> **I programmed the landscape and material, the particle effects like the snow on the mountain, and the ally and enemy AI. The landscape material is generated proceduarlly based on altitude (getting snowier the higher you get) and angle (making sheer cliff faces into rocks). The ally and enemy AI both extend from the same parent character AI class I wrote. Allies attack enemies and enemies attack allies (while preferring to target the player). AI will retaliate against attacks and attack AI who attack them.** 
>

## [Unreal Python Sudoku Solver](https://github.com/RyanAWalters/UnrealPythonSudokuSolver)
>
> This is a sudoku puzzle solver written in Python that interfaces with Unreal Engine for the GUI.
>
> In this team project, we created a python script to generate and solve sudoku puzzles. It does this by using constrained back-propogation algorithms. But we needed a user interface. I used Unreal Engine and created a sudoku puzzle class and made a simple script that solved the puzzle with a brute force algorithm (significantly slower that the Python script, for effect). Instead of translating the Python code to C++, I used a plugin that allows for OS process creation and created an interface between Unreal Engine and Python.
>

# Large Personal Projects

## :white_check_mark: [Puxxle (Mobile Game)](https://github.com/RyanAWalters/Puxxle)
>
> <p align="left"><img src="https://github.com/RyanAWalters/Puxxle/raw/master/img/icon.webp" width=50></p> 
>
> Puxxle is a unique puzzle game in which you tap on squares of alternating colors. Make all colors the same to win. The fun lies in discovering the algorithms to solve the puzzles as well as challenging records.  
>
> You can read more about it on its [Google Play Store page.](https://play.google.com/store/apps/details?id=com.illiquid.puzzle)
>
> #### [Or, you can even play it right now in your desktop browser!](https://ryanawalters.github.io/Puxxle/)
>
>
> **This game was made completely by myself in the Summer of 2016. It is made in Unreal Engine and is published to the Google Play Store. The game implements saving, digital currency, and in-app purchases for Android, as well as record tracking and random puzzle generation controllable by seeds.**
>
> ### [Find out more on the GitHub page](https://github.com/RyanAWalters/Puxxle)

# Personal Projects

### :white_check_mark: [Power of 2 Image Resizer - Game Engine Texture Optimization](https://github.com/RyanAWalters/PowerOf2ImageResizer)
>
> I made this program to scale images to a power of 2 size to facilitate their use as textures in game engines. It is written in Python but is packaged as a binary that is installed on your Windows computer. This is required for the shell extension I wrote that allows the user to simply right-click on images and scale them right there in the file manager. The compression level and scaling threshold are user configurable by editing configuration file.
>
> **[If you are unsure what exactly this is for, or you are intersted in downloading it for yourself, visit the GitHub page here.](https://github.com/RyanAWalters/PowerOf2ImageResizer)**
>
> This Python program uses the [Pillow fork of the Python Imaging Library (PIL)](https://github.com/python-pillow/Pillow) and [PyGame](https://github.com/pygame/pygame) to process images. I wrote this for my personal use to solve a problem I had and save myself a significant amount of time in my regular workflow. I published it here in case anyone else would benefit from it.
>

### [Simple Python 3D Graphics Rendering Engine](https://github.com/RyanAWalters/SimplePython3DGraphicsEngine)
>
>
>
>

### [Advanced Python Lighting Model](https://github.com/RyanAWalters/PythonAdvancedLightingModeling)
>
>
>
>

# Smaller Assignments

### [Dimes and Quarters Problem - Optimal Solution Finder](https://github.com/RyanAWalters/DimesAndQuartersOptimizer)
>
>
>
>

### [Simple pl/0 Compiler](https://github.com/RyanAWalters/pl0-compiler)
>
>
>
>
