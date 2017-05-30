#include "File.au3"

$currentExeVersion=1.1
$currentIniVersion=1.1
$versionIni = @ScriptDir & "\Clips\version.ini"
$clipDirectory = @ScriptDir & "\Clips\"

If IniRead($versionIni,"Version","IniVersion","0") < $currentIniVersion Then Install()
If FileExists(@ScriptDir & "\Clips\")=0 Then Install()
	
;; Using Hotkeys
HotKeySet("^1","UseHotKey1")
HotKeySet("^2","UseHotKey2")
HotKeySet("^3","UseHotKey3")
HotKeySet("^4","UseHotKey4")
HotKeySet("^5","UseHotKey5")
HotKeySet("^6","UseHotKey6")
HotKeySet("^7","UseHotKey7")
HotKeySet("^8","UseHotKey8")
HotKeySet("^9","UseHotKey9")
HotKeySet("^0","UseHotKey0")

HotKeySet("^{F1}","UseHotKeyF1")
HotKeySet("^{F2}","UseHotKeyF2")
HotKeySet("^{F3}","UseHotKeyF3")
HotKeySet("^{F4}","UseHotKeyF4")
HotKeySet("^{F5}","UseHotKeyF5")
HotKeySet("^{F6}","UseHotKeyF6")
HotKeySet("^{F7}","UseHotKeyF7")
HotKeySet("^{F8}","UseHotKeyF8")
HotKeySet("^{F9}","UseHotKeyF9")
HotKeySet("^{F10}","UseHotKeyF10")
HotKeySet("^{F11}","UseHotKeyF11")
HotKeySet("^{F12}","UseHotKeyF12")

HotKeySet("^-","ShowClipContents")


;; Setting Hotkeys
HotKeySet("^+1","SetHotKey1")
HotKeySet("^+2","SetHotKey2")
HotKeySet("^+3","SetHotKey3")
HotKeySet("^+4","SetHotKey4")
HotKeySet("^+5","SetHotKey5")
HotKeySet("^+6","SetHotKey6")
HotKeySet("^+7","SetHotKey7")
HotKeySet("^+8","SetHotKey8")
HotKeySet("^+9","SetHotKey9")
HotKeySet("^+0","SetHotKey0")

HotKeySet("^+{F1}","SetHotKeyF1")
HotKeySet("^+{F2}","SetHotKeyF2")
HotKeySet("^+{F3}","SetHotKeyF3")
HotKeySet("^+{F4}","SetHotKeyF4")
HotKeySet("^+{F5}","SetHotKeyF5")
HotKeySet("^+{F6}","SetHotKeyF6")
HotKeySet("^+{F7}","SetHotKeyF7")
HotKeySet("^+{F8}","SetHotKeyF8")
HotKeySet("^+{F9}","SetHotKeyF9")
HotKeySet("^+{F10}","SetHotKeyF10")
HotKeySet("^+{F11}","SetHotKeyF11")
HotKeySet("^+{F12}","SetHotKeyF12")


While 1
	Sleep(100)
WEnd

Exit

Func ShowClipContents()
	Run("explorer.exe " & $clipDirectory)
EndFunc

Func UseHotKey1()
Send(FileRead($clipDirectory & "\1.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey2()
Send(FileRead($clipDirectory & "\2.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey3()
Send(FileRead($clipDirectory & "\3.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey4()
Send(FileRead($clipDirectory & "\4.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey5()
Send(FileRead($clipDirectory & "\5.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey6()
Send(FileRead($clipDirectory & "\6.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey7()
Send(FileRead($clipDirectory & "\7.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey8()
Send(FileRead($clipDirectory & "\8.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey9()
Send(FileRead($clipDirectory & "\9.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKey0()
Send(FileRead($clipDirectory & "\0.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc

Func UseHotKeyF1()
Send(FileRead($clipDirectory & "\F1.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF2()
Send(FileRead($clipDirectory & "\F2.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF3()
Send(FileRead($clipDirectory & "\F3.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF4()
Send(FileRead($clipDirectory & "\F4.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF5()
Send(FileRead($clipDirectory & "\F5.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF6()
Send(FileRead($clipDirectory & "\F6.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF7()
Send(FileRead($clipDirectory & "\F7.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF8()
Send(FileRead($clipDirectory & "\F8.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF9()
Send(FileRead($clipDirectory & "\F9.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF10()
Send(FileRead($clipDirectory & "\F10.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF11()
Send(FileRead($clipDirectory & "\F11.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc
Func UseHotKeyF12()
Send(FileRead($clipDirectory & "\F12.txt"),1)
Send("{CTRLDOWN}{CTRLUP}")
EndFunc


Func SetHotKey1()
	_FileCreate($clipDirectory & "\1.txt")
	FileWrite($clipDirectory & "\1.txt",ClipGet())
EndFunc
Func SetHotKey2()
	_FileCreate($clipDirectory & "\2.txt")
	FileWrite($clipDirectory & "\2.txt",ClipGet())
EndFunc
Func SetHotKey3()
	_FileCreate($clipDirectory & "\3.txt")
	FileWrite($clipDirectory & "\3.txt",ClipGet())
EndFunc
Func SetHotKey4()
	_FileCreate($clipDirectory & "\4.txt")
	FileWrite($clipDirectory & "\4.txt",ClipGet())
EndFunc
Func SetHotKey5()
	_FileCreate($clipDirectory & "\5.txt")
	FileWrite($clipDirectory & "\5.txt",ClipGet())
EndFunc
Func SetHotKey6()
	_FileCreate($clipDirectory & "\6.txt")
	FileWrite($clipDirectory & "\6.txt",ClipGet())
EndFunc
Func SetHotKey7()
	_FileCreate($clipDirectory & "\7.txt")
	FileWrite($clipDirectory & "\7.txt",ClipGet())
EndFunc
Func SetHotKey8()
	_FileCreate($clipDirectory & "\8.txt")
	FileWrite($clipDirectory & "\8.txt",ClipGet())
EndFunc
Func SetHotKey9()
	_FileCreate($clipDirectory & "\9.txt")
	FileWrite($clipDirectory & "\9.txt",ClipGet())
EndFunc
Func SetHotKey0()
	_FileCreate($clipDirectory & "\0.txt")
	FileWrite($clipDirectory & "\0.txt",ClipGet())
EndFunc
Func SetHotKeyF1()
	_FileCreate($clipDirectory & "\F1.txt")
	FileWrite($clipDirectory & "\F1.txt",ClipGet())
EndFunc
Func SetHotKeyF2()
	_FileCreate($clipDirectory & "\F2.txt")
	FileWrite($clipDirectory & "\F2.txt",ClipGet())
EndFunc
Func SetHotKeyF3()
	_FileCreate($clipDirectory & "\F3.txt")
	FileWrite($clipDirectory & "\F3.txt",ClipGet())
EndFunc
Func SetHotKeyF4()
	_FileCreate($clipDirectory & "\F4.txt")
	FileWrite($clipDirectory & "\F4.txt",ClipGet())
EndFunc
Func SetHotKeyF5()
	_FileCreate($clipDirectory & "\F5.txt")
	FileWrite($clipDirectory & "\F5.txt",ClipGet())
EndFunc
Func SetHotKeyF6()
	_FileCreate($clipDirectory & "\F6.txt")
	FileWrite($clipDirectory & "\F6.txt",ClipGet())
EndFunc
Func SetHotKeyF7()
	_FileCreate($clipDirectory & "\F7.txt")
	FileWrite($clipDirectory & "\F7.txt",ClipGet())
EndFunc
Func SetHotKeyF8()
	_FileCreate($clipDirectory & "\F8.txt")
	FileWrite($clipDirectory & "\F8.txt",ClipGet())
EndFunc
Func SetHotKeyF9()
	_FileCreate($clipDirectory & "\F9.txt")
	FileWrite($clipDirectory & "\F9.txt",ClipGet())
EndFunc
Func SetHotKeyF10()
	_FileCreate($clipDirectory & "\F10.txt")
	FileWrite($clipDirectory & "\F10.txt",ClipGet())
EndFunc
Func SetHotKeyF11()
	_FileCreate($clipDirectory & "\F11.txt")
	FileWrite($clipDirectory & "\F11.txt",ClipGet())
EndFunc
Func SetHotKeyF12()
	_FileCreate($clipDirectory & "\F12.txt")
	FileWrite($clipDirectory & "\F12.txt",ClipGet())
EndFunc

Func Install()
	DirCreate($clipDirectory)
	_FileCreate($versionIni)
	_FileCreate($clipDirectory & "\1.txt")
	_FileCreate($clipDirectory & "\2.txt")
	_FileCreate($clipDirectory & "\3.txt")
	_FileCreate($clipDirectory & "\4.txt")
	_FileCreate($clipDirectory & "\5.txt")
	_FileCreate($clipDirectory & "\6.txt")
	_FileCreate($clipDirectory & "\7.txt")
	_FileCreate($clipDirectory & "\8.txt")
	_FileCreate($clipDirectory & "\9.txt")
	_FileCreate($clipDirectory & "\0.txt")
	
	_FileCreate($clipDirectory & "\F1.txt")
	_FileCreate($clipDirectory & "\F2.txt")
	_FileCreate($clipDirectory & "\F3.txt")
	_FileCreate($clipDirectory & "\F4.txt")
	_FileCreate($clipDirectory & "\F5.txt")
	_FileCreate($clipDirectory & "\F6.txt")
	_FileCreate($clipDirectory & "\F7.txt")
	_FileCreate($clipDirectory & "\F8.txt")
	_FileCreate($clipDirectory & "\F9.txt")
	_FileCreate($clipDirectory & "\F10.txt")
	_FileCreate($clipDirectory & "\F11.txt")
	_FileCreate($clipDirectory & "\F12.txt")
	
	IniWrite($versionIni,"Version","IniVersion",$currentIniVersion) 
	IniWrite($versionIni,"Version","ExeVersion",$currentExeVersion)
EndFunc
