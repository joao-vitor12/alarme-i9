# alarme-i9
Development of an alarm in python

The project aims to develop an "alarm" in python with a "config.ini" file. For this, I imported the time, datatime, pytz and configparser libraries.

The config.ini file contains the date and time chosen for the alarm, as well as the message it should show.

For the development of the code in python to occur correctly, first, I read the config.ini file and saved the date, time and message in different variables. After that, through the "while True" repetition loop, which is repeated every 30 seconds by the "time.sleep(30)" function, I performed comparisons between the alarm variables and the present moment obtained through the "datetime .now()" and passed it to Brasilia's time zone. Thus, it was possible to trigger and display the alarm message at the correct time.
