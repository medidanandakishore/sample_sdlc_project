
# Requirements: #

# 1 Tetris #
# Gameplay
A random sequence of shapes, composed of square blocks, fall down a playingfield over time. The objective of the game is to manipulate these shapes, by 
moving each one sideways or rotating it by 90 degrees, to create a continuous 
horizontal line of blocks connecting the sides of the playing field. When a line of 
blocks is successfully created, that line disappears and any blocks above the 
deleted line will move down one line. The player receives points every time they 
cause a line to disappear. However, if lines are not successfully cleared they will 
begin to pile-up and fill the playing field. When the pieces stack, without being 
cleared, and reach the top of the board the game ends. The objective of the game 
is to receive as many points as possible before the game ends.

Tetris Piece
A shape composed of square blocks.
1 Tetrominoes
A geometric shape composed of four blocks, connected orthogonally.
 The 
colors shown in the the sections below may not actually represent the colors used 
in game.
2.Block
four blocks in a straight line.
3.Block
a row of three blocks with one added below the right side.
4. Block
a row of three blocks with one added below the left side.


Visual Studiocode 

Microsoft Visual Studio is an integrated development environment (IDE) from Microsoft. It can 
be used to develop console and graphical user interface applications along with Windows 
Forms applications, web sites, web applications, and web services in both native code together 
with managed code for all platforms supported by Microsoft Windows, Windows Mobile, 
Windows CE, .NET Framework, .NET Compact Framework and Microsoft Silverlight.

Keyboard
Any keyboards in this document refer to a 104-Key PC QWERTY style keyboard


# Introduction #

2.1 Preface
This document acts as a Software Requirements Specification for the project. It defines the 
programs functionality, capabilities, performance, and limitations.
2.2 Description
The objective of the project is to build a working, three-dimensional, Tetris game that can be 
played free of bugs with alterations to the classic game to make it more user-friendly, fun, and 
challenging. The game is meant to be open source and will be created under GNU General 
Public License v3 guidelines. The game will be playable as a single player game and meant to 
act as an enhanced version of the classic. Players will be able to enjoy various game modes 
allowing them to play the classic Tetris or new modes that put a new “spin” on the classic 
game. The game play changes for the new modes may include items that help or harm the 
player, importable music selection, different block shapes, a selection of skins, a marathon 
mode and time-trial mode.
2.3 Scope
The program will be written in the C# programming language as a stand-alone application. C# is 
a language that has gained popularity and is intended to be a simple, modern, general-purpose, 
object-oriented programming language. The program will also make use of new technologies 
such as the Microsoft XNA Framework. XNA is a toolset that was developed to provide an 
environment for game developers to focus primarily on “high-level” game development and 
less on “low-level” process development. The interface will use both 2D and 3D aspects of the 
XNA framework. The actual gameplay will exist on a 2D-grid that is placed inside of a 3D 
“world”. The pieces will be made in 3D and will be played within the 2D-grid. The 2D grid is 
only used as a visible guideline for the player to use when measuring where each piece will go. 
The user interface display, including menus, buttons, score, and other notifications will be in 
2D. This overlaying 2D user interface will act as a type of lens that the user is constantly looking 
through as the user plays the game. The 2D interface is not meant to hinder the users 
experience by blocking sight of the 3D “world” in any way. The design, layout, audio, graphic 
textures, and flow of the interface will all have to be developed.
2.4 Health Hazards and Dangers
While some people may not consider video games dangerous or trivialize their risks, it is 
important to be a responsible developer by considering them and inform the user of any risks. 
Although we will not take any specific actions to protect the user from these risks, we will 
inform them briefly of the risks in the opening splash screens of the game. It is ultimately up to 
the user to user the program safely and responsibly.

Repetitive Stress Injury

Using a keyboard, mouse, or game controller can cause stress injuries if used 
chronically or used for extended periods of time.

2.4.3 Eye Strain

Sitting in front of a computer screen can cause eye strain on the user. It is 
recommended the user take a five minute break every hour of play or if they 
experience eye strain, headaches, or blurry vision. If the user is experiencing eye 
strain, headaches, or blurry vision they should stop playing until these symptoms 
stop.

Neglect of Real Life Responsibilities

Playing video games can cause people to neglect their real life responsibilities. It 
is important to remember to play responsibly


