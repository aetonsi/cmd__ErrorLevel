# cmd__ErrorLevel
Simple Windows cli tool to alter the ERRORLEVEL. Can be called by any shell that can invoke batch files.

# Usage
Powershell:
```powershell
.\errorlevel.cmd 11
echo $LASTEXITCODE # prints 11
```

cmd:
```batch
errorlevel 11
echo %ERRORLEVEL%
REM prints 11
```
