# InnoSetup 5.x/6.x constants converters

[![Latest Version](https://img.shields.io/github/release/Wilenty/Inno-Setup-5.x-6.x-constants-converters.svg)](https://github.com/Wilenty/Inno-Setup-5.x-6.x-constants-converters/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/Wilenty/Inno-Setup-5.x-6.x-constants-converters/total.svg)](https://github.com/Wilenty/Inno-Setup-5.x-6.x-constants-converters/releases)
[![Latest Release Downloads](https://img.shields.io/github/downloads/Wilenty/Inno-Setup-5.x-6.x-constants-converters/latest/total.svg)](https://github.com/Wilenty/Inno-Setup-5.x-6.x-constants-converters/releases/latest)

If my tool helps you in any way, please support me.<br>
<br>
There you can check if, for example, you entered the constants correctly in your installer, which you are just creating. As well as you can expand all constants or change the entire command to constants for Inno Setup.<br>
<br>
Without the given constant, it shows possible constants that can be used to convert local paths, just select the appropriate Inno Setup version.<br>
You can save the expanded constants for future use. Just select all text ([ctrl]+[a]), then copy ([ctrl]+[c]), and paste it in any editor ([ctrl]+[v]), like a notepad, then save it to a file.<br>
<br>
Any error in the conversion of constants is displayed separately in this way: [->error message<-]<br>
So, with my tool you can find where you made a mistake. Of course the converters does not expands functions and/or procedures which exists in your script in the [Code] section, as with non-existent custom messages (cm:) and others.<br>
<br>
I prepared some screenshots of the program, where it converts Inno Setup constants into local paths or it converts local paths into constants.<br>
<br>
I have also added cmd scripts to run these converters in Administrative mode for IS6 (Inno Setup 6.x).<br>
<br>
Below some commands to check the converters.<br>
<br>
Convert constants to local paths:<br>
<b>{cmd} /c copy /y {sys}\drivers\etc\hosts {sys}\drivers\etc\hosts.MyBackup</b><br>
<br>
Convert local paths to constants (if your OS is installed on "c:" drive):<br>
<b>C:\Windows\system32\cmd.exe /c copy /y C:\Windows\system32\drivers\etc\hosts.MyBackup C:\Windows\system32\drivers\etc\hosts</b><br>
