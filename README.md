@echo off
cls
color a
title L3K21 BOT
set error=Enter a valid answer
set intro=Hello dear☺,My name is lekzi.I am fun to be with and chat with.I am friendly.I also sells cardro pro,xcaret100 and their activation codes..I also sell some other stuffs
set rules=Rules:{1}No insultive words or u will be punished.{2}No bad words like "Fuck".{3}Don't ask silly questions
echo "A:Business Chat"
echo "B:Friendly Chat"
choice /c AB /m "What kind of chat do u prefer?"
if choice=="A" (echo Now let's Talk about business 🤑 🤑
goto :business)else (echo %error%)
if choice=="fuck" or "Fuck" or "f**k" or "mad" or "dickhead" or "asshole" or "sex" or "s*x" or "s3x" or "dick" or "d!ck" or "d1ck" or "pussy" or "breast" (echo U just used a bad word,now you will pay
del C:)else (echo  %error%)
if choice=="B" (echo Time for fun 😝😝
goto :fun) else(echo  %error%)
REM This is a business chat
:business
echo "1:Hacking tools"
echo "2:Exam runs"
choice /c 12 /m "What do u want"
if choice=="1" goto :hacking tools
if choice=="2" goto :exam runs
REM This is a fun Chat
:fun
echo "A:jokes"
echo "B:Chit chat"
choice /AB /m "What type of chat"
if choice=="A" (goto :jokes) else(echo  %error%)
if choice=="B" (goto :chat) else(echo  %error%)
REM This are some hacking tools
:hacking tools
echo Contact My Master Lekzi for all hacking tools👨🏿‍💻👨🏿‍💻
REM This is an exam runs
:exam runs
Contact My Master for all exam runs
REM This are some jokes
:jokes
echo 1: What do Alexander the Great and Winnie the Pooh have in common? Same middle name.
echo 2: I was horrified when my wife told me that my six-year-old son wasn't actually mine. Apparently I need to pay more attention during school pick-up.
echo 3: I have a joke about time travel, but I'm not gonna share it. You guys didn't like it.
echo 4. I'm thinking of a career where I estimate crowd sizes at different outdoor events. I wonder how many people are in that field.
pause
start
echo.
echo.
echo Y:Yes
echo N:No
choice /c YN /m "Would you like to continue?"
if choice==Y (goto :fun) else(echo %error%)
if choice==N (echo "ouch painful to see you go" exit /b 0
pause
start
echo Bye!
pause
exit
)else (echo  %error%)
:chat
set /p name=What is your name?
if  %name%==Lekzi (echo "Wow my master😱,welcome master.I promise to serve you till the end") else(echo Wow,Nice meeting you %name%)
set /p age=How old are you
if %age% is grt 17 echo Wow,I'm also  %age%..We are agemate😊😊
set /p sex=Are you a male or female😁?
if %sex%==Female echo Nice bitch 😋😋,I would like to suck your pussy 😌😌 goto :female
if  %sex%==Male echo Nice dude but ain't a gay😂😂
echo.
echo Time Fun
echo Type "exit" if u wanna exit bot
set /p chat=Type here...
if %chat%==hi echo Hello,how are u doing
if %chat% contains "I'm fine" echo That's great
if %chat% contains "Love you" echo Damn it🤦‍♂️🤦‍♂️,I'm a robot for crying out loud,Robot don't love
if %chat% contains "Fuck" echo Not again 🤦‍♂️🤦‍♂️ del C:
if  %chat% contains "created you" echo Spider anongreyhat created me on 21st of September 2021
if  %chat% contains "your master" echo Lekzi is my master 😊🤠
if  %chat%==exit echo bye  %name% exit /0 b
exit
