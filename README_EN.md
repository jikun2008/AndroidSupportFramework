# AndroidSupportFramework - AOSP Development Assistant
[中文README.md / 中文版](README.md)
## Preface

After switching from Android application development to system development, I found working with Framework code in Android Studio rather cumbersome. There is no intelligent code completion or direct source code navigation, forcing manual searches to trace logic. The same issues exist in VS Code, resulting in low development efficiency.
This inspired me to build a tool enabling one-click import of JAR packages and header files within IDEs to optimize the development experience. Developed and polished intermittently over three years, this plugin has accumulated over 70,000 downloads and is now officially introduced in detail.

## Advantages

Supports Java and C/C++ projects. JAR loading takes roughly 1 to 2 minutes, while C++ project loading costs around 3 to 4 minutes. No more slow initialization caused by idegen.

## About AndroidSupportFramework

The plugin is available for download via the plugin marketplace of Android Studio, CLion and IntelliJ IDEA Community (up to version 2025.2).

![演示图](image/1.jpg "下载界面")

## Features

### Syntax highlighting and hints for Android.mk and Android.bp files

![演示图](image/2.gif "语法")

### Java Projects 
One-click JAR package loading supported

> A full successful source code build is required beforehand

> Compatible with Android Studio and IntelliJ IDEA Community

![演示图](image/3.jpg "java")

### C/C++ Projects 
One-click generation and automatic loading of CMakeLists.txt files

> A full successful source code build is required beforehand

> 这个功能需要提前编译成功一次源码

![演示图](image/4.jpg "c/c++")

You can freely jump to and browse source code afterwards.

