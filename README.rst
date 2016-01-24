cabinet
=======
This is a simple python module providing the ability to read windows .cab files.
It provides a CabinetFile object with a similar functionality to zipfile.ZipFile.

Based on the cabinet SDK, available from http://support.microsoft.com/kb/310618
Also reuses some code from zipfile.py

Since it ises ctypes to interface with the cabinet.dll file included with windows,
this code works on Windows only.  
