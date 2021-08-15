# NI Programming Guide

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

The programming guidebook of code development in Next-Innovation(NI).

The guidebook is designed by the rules:

- Speed-only is not everything,  both the speed and readability are.
- Under the premise of speed , readability is everything.
- Under the premise of readability,  shorter is better.

Every developer should follow the rules when programming and pushing the code. 

This guidebook contains:

1. Good VS-Code extensions.
2. The code style.
3. Commit message format.
4. Process of developing new functions.

![NEXT_Innovation](https://github.com/FRCNextInnovation/NI-Programming-Guide/blob/main/assets/Logo_Purple_Word_Transparent.png)

## Table of Contents
- [VS-Code-Extensions](#VS-Code-Extensions)
- [Code-Style](#Code-Style)
  - [Source-File](#Source-File)
  - [Class](#Class)
  - [Variable](#Variable)
  - [Method](#Method)

## 1. VS-Code-Extensions

- [WPILIB](https://marketplace.visualstudio.com/items?itemName=wpilibsuite.vscode-wpilib)
- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [google-java-format](https://marketplace.visualstudio.com/items?itemName=ilkka.google-java-format)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

## 2. Code-Style

### 2.1 Source-File

- Naming: UpperCamelCase

  ![Source-File-UpperCamelCase](https://github.com/FRCNextInnovation/NI-Programming-Guide/blob/main/assets/Code/Source-File-UpperCamelCase.png)

- Structure: 

  1. License or copyright information(if present).
  2. Package statement.
  3. [Import](#Import) statements.
  4. [Class](#Class) statements.

#### 2.1.1 License or copyright information

- Example:

#### 2.1.2 Package statement

- No line-wrapped.
- The package statement should be divided from Import statements by a blank line.

#### 2.1.3 Import statements

- Static import or otherwise are not used.

- No line-wrapped.

- Import from same package should be put together.

- Import from different package should be divided by a single blank line.

- Example:

  Bad:

  <img src="https://github.com/FRCNextInnovation/NI-Programming-Guide/blob/main/assets/Code/Import-Bad.png" alt="Import-Bad" style="zoom:67%;" />

  Good:

  <img src="https://github.com/FRCNextInnovation/NI-Programming-Guide/blob/main/assets/Code/Import-Good.png" alt="Import-Good" style="zoom:67%;" />