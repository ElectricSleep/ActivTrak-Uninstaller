REM Script called from uninstaller to ensure that svctcom is stopped and deleted

taskkill /F /IM scthost.exe
taskkill /F /IM trmhost.exe
taskkill /F /IM syschk.exe
taskkill /F /IM svctcom.exe

sc stop svctcom
sc delete svctcom
