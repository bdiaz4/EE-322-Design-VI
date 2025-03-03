# Python
## `cd ~/iot` AND `cd *3`
![image](https://github.com/user-attachments/assets/35141126-3ad5-49a4-a31b-6411bfff0e51)\
First to access the python files we change the current directory to the cloned iot repository and go to the lecture 3 folder. The ~ makes iot the current home directory we will return to. The * after cd goes to the directory that has a 3 in its name, so cd * can be a good way to get to a directory without knowing the full name.
## python3 julian.py
![image](https://github.com/user-attachments/assets/85f50420-c973-4e8c-b2dd-817f9f40d60a)\
When first trying to run julian.py using the command `python3` it can not import jdcal so we use `pip instal jdcal` to import the needed package. The script itself prints the calendar date, and the converted Julian and Modified Julian date. The Julian date is a continuous count of days and fractional time in the day since noon Universal Time on January 1, 4713 BC while the Modified Julian date is days since midnight on November 17, 1858. 
## python3 date_example.py
![image](https://github.com/user-attachments/assets/e3d3ca78-d156-4830-9b0a-b330e2d0b8d3)\
This script prints the date in yyyy-mm-dd and mm-dd-yyyy, prints the day of the week, month, year, and the days after the first lecture as well as before the last lecture in the class.
## python3 datetime_example.py
![image](https://github.com/user-attachments/assets/ae2c5292-5dd8-419d-afb8-dbd873cd83f8)\
This script prints the time in date and several other formats. The 3rd print gives the current time in UTC. The 4th time not in a normal format is returning the number of seconds passed since epoch on January 1, 1970, 00:00:00 UTC.
## python3 time_example.py
![image](https://github.com/user-attachments/assets/7cc89723-eada-4f19-b7c3-2082aacfaf8a)\
This script will print the time utilizing the format 5th output in the previous example. It will keep printing the current time to the console until it is interrupted by the keyboard input ctrl c `^c`.
## python3 sun.py "New York"
![image](https://github.com/user-attachments/assets/381d0fa9-335b-4375-89b3-e8aaf1492621)\
This script required a download of the packages pytz and astral. The script itself prints information about New York, including the timezone, latitude, longitude, and when dawn, sunrise, noon, sunset, and dusk occur at this location.
## python3 moon.py
![image](https://github.com/user-attachments/assets/af98301f-2f36-42d6-bcd6-bf57ec2c1491)\
This script gives the current phase of the moon in days-1 since the new moon. The script than prints the remaining future days until the current phase of the moon repeats. 
## python3 coordinates.py "Samuel C. Williams Library"
![image](https://github.com/user-attachments/assets/1740fd34-7cf5-415c-97c2-f5c8a6fc6f25)\
This script required a download of the package geopy. The script itself prints information about the argument Samuel C. Williams Library and latitude and longitude.
## python3 address.py "40.74480675, -74.02532861159351"
![image](https://github.com/user-attachments/assets/d6a2c061-4bb6-4bd1-9733-79930fcaf2ff)\
This script is similar to coordinates.py except it gives the address given the coordinates instead of the coordinates given the address.
## python3 cpu.py

## python3 battery.py
## python3 documentstats.py document.txt


