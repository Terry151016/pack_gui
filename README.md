# pack_gui
打包工具：PyInstaller （cx_Freeze）

打包流程：1.安装打包工具
                      2.进入代码目录： 打开命令行终端，导航到存储代码的目录
                      3.使用PyInstaller打包应用程序 

PyInstaller提供了许多参数和选项，用于定制打包过程。

--onefile：将应用程序打包成单一可执行文件，而不是文件夹。这个选项会将所有依赖项打包到一个文件中。 示例：pyinstaller --onefile my_script.py

--windowed：生成一个无命令行窗口的GUI应用程序。这在打包GUI应用程序时很有用。 示例：pyinstaller --windowed my_script.py
