# lowBatteryNotification
Custom low battery notification for ubuntu 18.04

step 1

	install mpg123 package

	make sure its working correctly

step 2

	change the notification sound in script

	its corrently "/home/anuragjk/.extras/low_battery_sound.mp3"

step 3

	add a new crontab entry

	$ crontab -e

	* * * * * /path/to/script/low_battery_check
