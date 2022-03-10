# cl.exe环境配置

1. vscode配置可直接复用，只需修改特定环境目录
2. 添加cl.exe到Path环境下
3. 添加LIB环境变量:是本地vs安装目录而定
    G:\VisualStudio2022\VC\Tools\MSVC\14.30.30705\lib\x64
    C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\ucrt\x64
    C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x64
4. 添加INCLUDE环境变量:
    G:\VisualStudio2022\VC\Tools\MSVC\14.30.30705\include
    C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\shared
    C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\ucrt
    C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\um
    C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\winrt
