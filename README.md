# WCH-CH347-XVCD-DAEMON
CH347 Xilinx Virtual Cable Daemon
xvcd_ch347 of XVC (Xilinx Virtual Cable) protocol based on xvcd (https://github.com/tmbinc/xvcd) 

Based on [xvcd-ch347](https://github.com/AIOT-CAT/xvcd-ch347)

# Claims
File `CH347DLL.h`, `CH347DLLA64.dll` are property/properties of WCH group, this project does not have the rights of them.

This project has ABSULUTELY NO WARRENTY, use this as researching purpose. For critical environments, use Xilinx's official download cables instead.

# Dependencies

1. WCH CH347 Device Driver, you can obtain it from [here](https://www.wch.cn/downloads/CH341PAR_EXE.html).
2. xmake
3. Windows 10 SDK or Windows 11 SDK, only 64 bit with x86_64 arch versions are supported.
4. msvc16 and later to have a better support for C.

# How to build
Install you dependencies first,then do `git clone https://github.com/DCZYewen/WCH-CH347-XVCD-Daemon`, and get into the project folder.

Run `xmake build` to build the project. You can also run `xmake run` to run the program directly.

If you wanted to debug it under Visual Studio, run `xmake project -k vsxmake`, it will create the Visual Studio `.sln` for you.

