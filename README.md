# ExcelDllLoader
Execute DLL via the Excel.Application object's RegisterXLL() method

Leran from Ryan Hanson‏ @ryHanson

Link：

https://gist.github.com/ryhanson/227229866af52e2d963cf941af135a52

License: BSD 3-Clause

Add the following functions:

- Check if Microsoft Office has been installed
- Download the dll from Github
- Save the dll to %appdata%\Microsoft\Windows\Recent
- Load it via the Excel.Application object's RegisterXLL() method

Note:

After the DLL is loaded, the DLL is automatically deleted.

But if you change the path that DLL saves(eg: c:\test),the dll will not be automatically deleted.
