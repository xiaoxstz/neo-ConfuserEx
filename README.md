ConfuserEx2
--------
# 1. Introduction
`ConfuserEx2` is a .NET program protector.
* [ConfuserEx2 on Github](https://github.com/xiaoxstz/ConfuserEx2)
* [ConfuserEx2 on Gitee](https://gitee.com/qqblack/ConfuserEx2)

# 2. History
* 2014.2-2016.7:[ConfuserEx](https://github.com/yck1509/ConfuserEx). This repository has been archived in Jan 27,2019
* 2018.5-now:[Neo ConfuserEx](https://github.com/XenocodeRCE/neo-ConfuserEx). This project turns not active since 2019.12
* 2022.3 - now :ConfuserEx2
    * This repository plans to save this project since 2022.3.22.

<p align="center">
  
[![Build status](https://img.shields.io/appveyor/ci/gruntjs/grunt.svg)](https://ci.appveyor.com/project/XenocodeRCE/neo-confuserex/build/artifacts)

</p>

# 3. Documentation

Please have a look at our WIKI
* [wiki on Gitee](https://gitee.com/qqblack/ConfuserEx2/wikis)
* [wiki on Github](https://github.com/xiaoxstz/ConfuserEx2/wiki)


# 4. Obfuscation Features
* Supports .NET Framework 2.0/3.0/3.5/4.0/4.5 and up to 4.7.2
* Symbol renaming (Support WPF/BAML)
* Protection against **debuggers/profilers**
* Protection against **memory dumping**
* Protection against **tampering (method encryption)**
* **Control flow** obfuscation
* **Constant/resources** encryption
* **Reference hiding** proxies
* **Type scrambler** obfuscation
* Disable **decompilers**
* **Embedding dependency**
* **Compressing output**
* Extensible plugin API


# 5. Usage
`Confuser.CLI <path to project file>`

The project file is a ConfuserEx Project (*.crproj).
The format of project file can be found in docs\ProjectFormat.md

You can also run the GUI application, `ConfuserEx.exe`

# 6. How to build
Step1. Run the command below 
```bash
git.exe submodule update --progress --init
```
Step2. Open the solution file `Confuser2.sln` with Visual Studio.
Then, build the solution.
# 7. Bug Report
This project is maintained on Github and Gitee
* [Issues in Github](https://github.com/xiaoxstz/ConfuserEx2/issues)
* [Issues in Gitee](https://gitee.com/qqblack/ConfuserEx2/issues): If you want to get quicker answer, you can create an reward in the issue tab.

# 8. License
See LICENSE file for details.

# 9. Credits
**[yck1509](https://github.com/yck1509)** the one and only, original coder of [ConfuserEx](https://yck1509.github.io/ConfuserEx/)

**[0xd4d](https://github.com/0xd4d)** for his awesome work and extensive knowledge!  

Members of **[Black Storm Forum](http://board.b-at-s.info/)** for their help!
