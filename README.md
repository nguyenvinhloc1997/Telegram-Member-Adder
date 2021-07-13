# Telegram-Member-Adder
This tool can scrap and add Telegram members from any group to your group. It has many more useful files like "filter by last seen", "private-public", "addauto", "ban filter" etc.


Basic requirement to run this tool Download :

Notepad++ : https://notepad-plus-plus.org/downloads/
Python : https://www.python.org/downloads/
Module Required : Open PowerShell in Administrator Mode and Type "pip install telethon" & "pip install Licensing" 

------------------------------------------------------------------------------------

Step 1. Open Phone.csv File in Notepad++ and then Enter your Telegram numbers

Step 2. Now open api.csv file in Notepad++ and Enter the api id & hash for those numbers (To get Api & Hash IDs use our bot : https;//t.me/Apiextractor_bot)

Step 3. Open Config.ini file in Notepad++ and Enter the main_Phone Number (choose any one from phone.csv)
        also enter the target Group username in 
        "from_channel" and put your group username in "to_channel"

Step 4. Now run the login file and enter OTPs and then login session will be saved in sessions folder

Step 5. Run Export file and scrap the members those members will be saved in unf.csv

Step 6. Now run Filter.py and FilterByLastSeen.py respectively these files will filter the data from unf.csv and will save them in data.csv

Step 7. Now edit memory.csv file, by default its 1,1,50 which means the automatic adder (autoadd.py) will pick first mobile number from phone.csv and it will start adding from 1st username to 50th username from data file. (No need to edit it each time it will be automatically edited when you'll run that file again and the memory file values will be 2,51,100)

Step 8. Now open ManualSelect Script folder and run addauto.py file which will start adding members

--------------------------------------------------------------------------------------

2nd line, Text now and many more applications are freely available by which you can create unlimited Telegram accounts to add members.
